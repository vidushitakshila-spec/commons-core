# commons-core
1. Problem statement: Applications lack consistent, lightweight base utilities, null-safety contracts, and shared exception hierarchies, leading to boilerplate error handling and scattered validation logic.

2. Concepts and terminology: Defensive programming, fail-fast assertions, root exception mapping, standard functional interfaces.

3. Available technologies / algorithms: Java 21 standard libraries, JUnit 5, AssertJ, Spring Core utilities.

4. When to use what: Use for cross-cutting utility functions, standard error envelopes, and base validation helpers across all downstream microservices.

5. Java APIs and dependencies: java.util.*, Spring Framework Assert, Lombok, SLF4J API.

6. AWS equivalents: AWS Lambda Common Layers, AWS SDK Core.

7. Architecture patterns: Shared Kernel pattern, Fail-Fast Validation, Immutable Data Transfer Objects (DTOs).

8. Security considerations: Prevent information leakage in generic error messages; ensure safe exception serialization.

9. Implementation examples: Custom BaseException hierarchy with error codes and context maps.

10. References and further reading: Clean Code (Robert C. Martin), Effective Java (Item rules on exceptions and immutability).
