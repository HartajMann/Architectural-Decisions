# ADR 3: Backend Language
The backend selection is driven by requirements for real-time order tracking, seamless payment gateway integrations, and consistent synchronization with restaurant inventories.
## Decision
We will use Node.js for the backend.

## Rationale
Node.js stands out as a top choice for our infrastructure due to its asynchronous, event-driven architecture, making it particularly suitable for real-time applications like order tracking.  The npm ecosystem, which is one of the largest software registries, provides a multitude of ready-to-use packages, facilitating rapid integration with services such as payment gateways or inventory management systems. Yet, it's essential to note that Node.js may not be the ideal option for CPU-bound tasks due to its single-threaded nature.
## Status
Accepted 

## Consequences
- Scalable backend
- Efficient real-time data handling
- Broad community support
