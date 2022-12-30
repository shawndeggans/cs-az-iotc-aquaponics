# Architecture Decision Records

The purpose of an architecture decision record is to capture an important architectural decision made along with its context and consequences. This information can be very valuable to understand the rationale behind the decision and the evolution of the system over time.

These are the baisic steps to create an ADR:

Context: A description of the problem or issue that the decision is addressing.
Decision: A clear statement of the decision that was made.
Alternatives: A description of the alternatives that were considered.
Consequences: A description of the potential positive and negative consequences of the decision.

Here is an example of an ADR:

## ADR 1: Database choice
### Context
We need to choose a database for storing user data in our application.

### Decision
We will use PostgreSQL as the database for our application.

### Alternatives
We considered the following alternatives:

MySQL: Widely used and well-supported, but does not support some advanced features that we may want to use in the future.
MongoDB: Good support for unstructured data, but does not offer the same level of transaction support as a traditional SQL database.

### Consequences
Positive: PostgreSQL is a well-respected database with strong support for advanced features and transactions. It should meet our needs for the foreseeable future.
Negative: It may be more difficult to find developers with experience in PostgreSQL compared to more widely used databases like MySQL.