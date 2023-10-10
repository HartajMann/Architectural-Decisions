# ADR 5: Data Storage
Fast data retrieval combined with scalable, secure, and remotely accessible storage solutions are key.

## Decision
We will use a combination of local storage like SQLite for lightweight data and caching and cloud-based solutions like Amazon Web Service for more substantial data and user information.

## Rationale
The dual approach to data storage is a response to the variety and nature of data the application handles. Local storage, with tools like SQLite, provides quick access and caching capabilities, ensuring that frequently used data, like a user's favoured orders, is readily available. On the other hand, cloud-based solutions like Amazon RDS assure scalability, providing a reliable solution for larger data sets. This approach also offers benefits like automated backups and ensuring data integrity availability.
## Status
Accepted
## Consequences
- Fast data retrieval
- Scalable storage solution
- Increased data security measures required for cloud storage.
