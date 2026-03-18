talk about something obvious but with a bit of quantification...

Theoretically, both arrays and linked lists take O(n) time to traverse, but here's what actually happens when you benchmark by summing 100k integers

- Array: 68,312 ns
- Linked List: 181,567 ns

Summing an array is ~3x faster than LinkedList. Same algorithm, same complexity, but wildly different performance.

The reason is cache behavior. When you access array[0], the CPU fetches an entire cache line (64 bytes), which includes array[0] through array[15]. The next 15 accesses are essentially free. Arrays hit the cache about 94% of the time.

Linked lists suffer from pointer chasing. Each node is allocated separately by malloc(), scattered randomly in memory. Each access likely requires a new cache line fetch, resulting in a 70% cache miss rate.

This is a good example of why Big O notation tells only part of the story. Spatial locality and cache-friendliness can make a 2-3x difference even when the theoretical complexity is identical.

