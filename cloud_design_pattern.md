𝗖𝗹𝗼𝘂𝗱 𝗗𝗲𝘀𝗶𝗴𝗻 𝗣𝗮𝘁𝘁𝗲𝗿𝗻𝘀 ☁️

These design principles can be used to create dependable, scalable, and secure cloud systems. We can group Cloud design patterns into three general groups, where each pattern can be to any distributed system, regardless of whether it is hosted on-prem or some cloud platform.

The main Cloud Design Pattern groups are:

📌 𝗗𝗮𝘁𝗮 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁

The main component of cloud applications is data management, which affects most of the quality criteria. Data is hosted across many servers and locations for performance, scalability, or availability. This could pose several difficulties. For instance, data synchronization between many places is often required to ensure data consistency.

This group has CQRS, Sharding, Index table, etc.

📌 𝗗𝗲𝘀𝗶𝗴𝗻 𝗮𝗻𝗱 𝗜𝗺𝗽𝗹𝗲𝗺𝗲𝗻𝘁𝗮𝘁𝗶𝗼𝗻

Maintainability to make administration and development easier, reusability to let components and subsystems be used in various applications and contexts, and consistency and
coherence in component design and deployment are all parts of good design. The quality and total cost of ownership of cloud-hosted applications and services are influenced by 
decisions made during the design and implementation phase.

In this (largest) group, we have Sidecar, Strangler fig, etc.

📌 𝗠𝗲𝘀𝘀𝗮𝗴𝗶𝗻𝗴

Because cloud applications are distributed, a messaging infrastructure is needed to link the various parts and services. This infrastructure should be loosely coupled to allow
for the largest scalability. Asynchronous messaging is popular and has many advantages but drawbacks, like sorting messages, managing poison messages, idempotency, and more.

This group has Priority Queue, Pub/Sub, etc.

📌 𝗦𝗲𝗰𝘂𝗿𝗶𝘁𝘆

Security protects information systems from hostile attacks by ensuring data confidentiality, integrity, and availability. Losing these guarantees might harm your company's operations, 
earnings, and reputation in the marketplace. Following accepted procedures and remaining watchful to spot and address vulnerabilities and active threats are necessary for maintaining
security.

In this group, we have Federated Identity and Gatekeeper.

📌 𝗥𝗲𝗹𝗶𝗮𝗯𝗶𝗹𝗶𝘁𝘆

When we say reliability, we usually mean the availability and resiliency of the system. The percentage of time that a system is operational and operating is called availability,
expressed as a percentage of uptime, while a system's resilience is its capacity to handle and bounce back from failures, purposeful and unintentional alike.

In this group, we have Bulkhead, Circuit breaker, etc.
