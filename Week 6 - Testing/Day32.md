✅ Better understood how to write integration tests

✅ Learned how to reset the database after each test using beforeEach and afterEach

-beforeEach in Jest is part of the setup and teardown process. As the name suggests, if we want to run a function or some other code repeatedly “before each” test that code can be put in the beforeEach function

- afterEach function that will run a piece of code every time a test has completed running a.k.a tear down. If we want to run some code only once before all the tests run, Jest has beforeAll function for that purpose

✅ Learned about different types of NoSQL database

Types of NoSQL databases

1. key-value

   - store key-value pairs
   - the key is the identifier, which must be unique
   - value is the data can be simple (string, integer) or complex
   - can be manipulated through CRUD
   - is not recommended for doing JOINS between data

   **Key-Value use-case**

a. Caching: storing frequently accessed data in memory rather than solely on disk for fast application response time

Cach = a key-value database

b. Session management: captures the current state of a user’s interaction with an app; provides a consistent, responsive UX

1. document store

- most popular NoSQL database
- document model oriented
- flexible schema ⇒ left the model to evolve as the app needs to change

ex. mongoDB, Couchbase

**Use-case**

- e-commerce app
- customer 360
- product catalog: data denormalization means all data relevant to a product can be stored in that product’s document
- real-time analytics

1. graph database

- store entities as nodes and relationships between entities as edges
- nodes (entities) have properties
- traversing relationships is very fast as it’s not calculated at query time but persisted
- well suited for connected data

ex. neo4j

1. column-family

- more complex type to understand
- store data as columns families contain rows; each row is identified by a key and has many columns

ex. cassandra, hbase

✅ Created our own codewars kata and tests
