Here are 10 common microservice patterns:

🔹 API Gateway Pattern: This pattern creates a single access point for client requests, directing them to the relevant microservice.

🔹 Bulkhead Pattern: This pattern isolates failures in a microservices architecture by placing each microservice in a separate container to
prevent one failure from impacting others.

🔹 Circuit Breaker Pattern: This pattern addresses failures in microservice architectures by rerouting requests to an alternative service 
when a microservice is unresponsive.

🔹 CQRS Pattern: This pattern separates read and write models in a microservices architecture, optimizing the read model for data querying
and the write model for data updating.

🔹 Event-Driven Architecture Pattern: This pattern uses events as a means of communication between microservices, allowing them to
publish and subscribe to each other's events.

🔹 Saga Pattern: This pattern manages transactions across multiple microservices by breaking them into smaller steps and utilizing
compensating actions to reverse completed steps in 
case of errors.

🔹 Service Mesh Pattern: This pattern adds an infrastructure layer between microservices to handle concerns such as load balancing, 
service discovery, and security.

🔹 Service Registry Pattern: This pattern maintains a central directory for service discovery, tracking all services in a microservices
architecture.

🔹 Sidecar Pattern: This pattern deploys an additional container alongside each microservice to handle cross-cutting concerns like logging, monitoring, and security.

🔹 Strangler Pattern: This pattern incrementally replaces a monolithic application with microservices, slowly introducing new microservices while removing functionality from the monolith
