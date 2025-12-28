# java-interview-questions

# Java Interview Questions – 4+ Years Experience

---

## Core Java Questions

1. Explain the differences between `==` and `.equals()` in Java, with examples.
2. What is the difference between checked and unchecked exceptions? Give examples.
3. How does garbage collection work in Java? Explain the role of different GC algorithms (e.g., G1, CMS).
4. What are the differences between `HashMap`, `LinkedHashMap`, and `ConcurrentHashMap`?
5. Explain the contract between `equals()` and `hashCode()`, and why it's important.
6. What is multithreading in Java? Explain thread lifecycle and methods like `start()`, `run()`, `join()`, and `sleep()`.
7. What is synchronization? Differentiate between synchronized methods and blocks.
8. Explain the `volatile` keyword and its use cases.
9. What are immutable objects? Why is `String` immutable in Java?
10. Explain Java Memory Model and happens-before relationship.
11. What is the difference between `ArrayList` and `LinkedList`?
12. How does fail-fast vs fail-safe iterator work in collections?
13. Explain the diamond problem in multiple inheritance and how Java handles it with interfaces.
14. What are functional interfaces? Give examples from `java.util.function`.
15. Explain reflection in Java and its pros/cons.

---

## Java 8+ Features

16. What are the major features introduced in Java 8?
17. Explain Lambda expressions with examples.
18. What is the Stream API? Demonstrate filtering, mapping, and reducing on a list.
19. What is `Optional` class? How does it help avoid `NullPointerException`?
20. Explain default and static methods in interfaces.
21. What is the difference between `Collection.stream()` and `Collection.parallelStream()`?
22. Explain method references with examples (e.g., `Class::method`).
23. What are the new Date/Time API features in Java 8 (`java.time` package)?
24. How do `CompletableFuture` and `ForkJoinPool` support asynchronous programming?
25. What changes were introduced in Java 11+ (e.g., `var`, HTTP Client, modules from Java 9)?

---

## OOP and Design Patterns

26. Explain the SOLID principles with Java examples.
27. What is dependency injection? How is it achieved in plain Java?
28. Name common design patterns (Singleton, Factory, Builder, Observer) and explain one with code.
29. What is the difference between composition and inheritance?
30. Explain abstraction vs encapsulation.

---

## Concurrency and Advanced Core

31. Explain `ExecutorService` and different thread pools (fixed, cached, single).
32. What is deadlock? How to detect and prevent it?
33. Difference between `ReentrantLock` and `synchronized`.
34. What are `CountDownLatch`, `CyclicBarrier`, and `Semaphore`?
35. Explain JVM internals: Heap, Stack, Metaspace, and class loading.

---

## Spring / Spring Boot Basics

36. What is Spring Boot? How does it differ from Spring Framework?
37. Explain `@SpringBootApplication` annotation and its components.
38. What is auto-configuration in Spring Boot?
39. How do you create a REST API in Spring Boot?
40. Explain `@RestController` vs `@Controller`.
41. What is Spring Data JPA? Explain `@Entity`, `@Repository`.
42. How does `@Autowired` work? What are alternatives (constructor injection)?
43. Explain `application.properties` vs `application.yml`.
44. What is Actuator in Spring Boot? Common endpoints.
45. How to handle exceptions globally in Spring Boot (`@ControllerAdvice`)?
46. What are profiles in Spring Boot? How to use them?
47. Explain Spring Security basics for a REST API.
48. Difference between `@Component`, `@Service`, `@Repository`.
49. How to integrate caching (e.g., `@Cacheable`) in Spring Boot?
50. What is Spring Boot DevTools and its benefits?

---

## Advanced JVM and Core Java

51. Explain JVM architecture in detail.
52. Types of Garbage Collectors in Java and comparison.
53. JVM tuning parameters and performance flags.
54. Causes of `OutOfMemoryError`.
55. Class loading mechanism and delegation model.
56. JIT compilation and tiered compilation.
57. Memory leak detection and analysis.
58. Weak, soft, and phantom references.
59. Java memory leaks with examples.
60. Java IO/NIO performance best practices.

---

## Hibernate / JPA Advanced

61. Hibernate caching mechanisms.
62. N+1 select problem and solutions.
63. Difference between `get()` and `load()`.
64. Hibernate entity states.
65. JPA inheritance strategies.
66. Dirty checking in Hibernate.
67. `@OneToMany` with cascade and orphan removal.
68. `@JoinColumn` vs `mappedBy`.
69. Optimistic vs pessimistic locking.
70. Custom types in JPA.

---

## Microservices with Spring Boot

71. Microservices architecture overview.
72. Spring Cloud components.
73. API Gateway implementation.
74. Distributed tracing.
75. Inter-service communication patterns.
76. Configuration management.
77. Circuit Breaker pattern.
78. Saga pattern.
79. Securing microservices.
80. Common microservices challenges.

---

## Spring Boot Advanced

81. Spring Boot Actuator deep dive.
82. Externalized configuration.
83. Spring WebFlux.
84. `@Transactional` propagation and isolation.
85. Custom auto-configuration.
86. Spring Boot starters.
87. Testing strategies.
88. Global exception handling.
89. JPA auditing.
90. Reactive programming with Project Reactor.

---

## Testing and Best Practices

91. Java coding best practices.
92. Unit vs integration testing.
93. Java profiling tools.
94. Mockito annotations.
95. Java records and sealed classes.

---

## Data Structures and Algorithms

### Arrays & Strings
96. Two Sum problem.
97. Merge sorted arrays.
98. Longest substring without repetition.
99. Rotate array.
100. Maximum subarray sum.
101. Palindrome check.
102. String reversal.
103. Find duplicates.
104. Rearrange positives and negatives.
105. Missing number.

### Linked List
106. Reverse linked list.
107. Detect/remove cycle.
108. Merge linked lists.
109. Middle of linked list.
110. Palindrome linked list.
111. LRU cache.
112. Add numbers as linked lists.
113. Flatten linked list.

### Trees & Graphs
114. Tree traversals.
115. Tree height.
116. Balanced tree.
117. Level order traversal.
118. Lowest common ancestor.
119. Serialize/deserialize tree.
120. Validate BST.
121. Construct BST.
122. Kth smallest/largest.

### Heap, DP, Misc
123. Heap implementation.
124. K largest elements.
125. Merge k sorted lists.
126. PriorityQueue internals.
127. BFS and DFS.
128. Cycle detection.
129. Shortest path.
130. Dijkstra algorithm.
131. Topological sort.
132. Sorting algorithms.
133. Binary search variations.
134. Sorting complexities.
135. Fibonacci DP.
136. LCS problem.
137. Knapsack problem.
138. Coin change.
139. Edit distance.
140. Trie implementation.
141. Sliding window maximum.
142. Rate limiter design.
143. Median from data stream.
144. HashMap collision handling.
145. Bit manipulation problems.


### Above list of questions are generated using Grok AI.
