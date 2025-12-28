# java-interview-questions

145 Java Interview Questions for 4+ Years Experience
Core Java Questions

Explain the differences between == and .equals() in Java, with examples.
What is the difference between checked and unchecked exceptions? Give examples.
How does garbage collection work in Java? Explain the role of different GC algorithms (e.g., G1, CMS).
What are the differences between HashMap, LinkedHashMap, and ConcurrentHashMap?
Explain the contract between equals() and hashCode(), and why it's important.
What is multithreading in Java? Explain thread lifecycle and methods like start(), run(), join(), and sleep().
What is synchronization? Differentiate between synchronized methods and blocks.
Explain volatile keyword and its use cases.
What are immutable objects? Why is String immutable in Java?
Explain Java Memory Model and happens-before relationship.
What is the difference between ArrayList and LinkedList?
How does fail-fast vs fail-safe iterator work in collections?
Explain the diamond problem in multiple inheritance and how Java handles it with interfaces.
What are functional interfaces? Give examples from java.util.function.
Explain reflection in Java and its pros/cons.

Java 8+ Features

What are the major features introduced in Java 8?
Explain Lambda expressions with examples.
What is the Stream API? Demonstrate filtering, mapping, and reducing on a list.
What is Optional class? How does it help avoid NullPointerException?
Explain default and static methods in interfaces.
What is the difference between Collection.stream() and Collection.parallelStream()?
Explain method references with examples (e.g., Class::method).
What are the new Date/Time API features in Java 8 (java.time package)?
How do CompletableFuture and ForkJoinPool support asynchronous programming?
What changes were introduced in Java 11+ (e.g., var, HTTP Client, modules from Java 9)?

OOP and Design Patterns

Explain the SOLID principles with Java examples.
What is dependency injection? How is it achieved in plain Java?
Name common design patterns (Singleton, Factory, Builder, Observer) and explain one with code.
What is the difference between composition and inheritance?
Explain abstraction vs encapsulation.

Concurrency and Advanced Core

Explain ExecutorService and different thread pools (fixed, cached, single).
What is deadlock? How to detect and prevent it?
Difference between ReentrantLock and synchronized.
What are CountDownLatch, CyclicBarrier, and Semaphore?
Explain JVM internals: Heap, Stack, Metaspace, and class loading.

Spring/Spring Boot Basics

What is Spring Boot? How does it differ from Spring Framework?
Explain @SpringBootApplication annotation and its components.
What is auto-configuration in Spring Boot?
How do you create a REST API in Spring Boot?
Explain @RestController vs @Controller.
What is Spring Data JPA? Explain @Entity, @Repository.
How does @Autowired work? What are alternatives (constructor injection)?
Explain application.properties vs application.yml.
What is Actuator in Spring Boot? Common endpoints.
How to handle exceptions globally in Spring Boot (@ControllerAdvice)?
What are profiles in Spring Boot? How to use them?
Explain Spring Security basics for a REST API.
Difference between @Component, @Service, @Repository.
How to integrate caching (e.g., @Cacheable) in Spring Boot?
What is Spring Boot DevTools and its benefits?

Advanced JVM and Core Java

Explain the JVM architecture in detail: Heap (Young/Old Generation), Stack, Metaspace, PC Register, Native Method Stack.
What are the different types of Garbage Collectors in Java (Serial, Parallel, CMS, G1, ZGC, Shenandoah)? Compare their pros/cons.
How do you tune JVM parameters for performance? Common flags like -Xms, -Xmx, -XX:+UseG1GC, etc.
What causes OutOfMemoryError? Differentiate between heap space and metaspace OOM.
Explain the class loading mechanism: Bootstrap, Extension, Application class loaders, and delegation model.
What is JIT compilation? Explain tiered compilation in HotSpot JVM.
How do you detect and analyze memory leaks in Java applications?
What is the difference between weak, soft, and phantom references?
Explain Java Memory Leaks with examples (e.g., unclosed resources, static collections).
What are the best practices for Java IO/NIO performance?

Hibernate/JPA Advanced

Explain Hibernate caching: First-level vs Second-level cache. How does Ehcache or Redis integrate?
What is the N+1 select problem in Hibernate/JPA? How to solve it (fetch join, entity graphs)?
Differentiate between get() and load() in Hibernate Session.
Explain Hibernate entity states: Transient, Persistent, Detached, Removed.
What are the inheritance mapping strategies in JPA (SINGLE_TABLE, JOINED, TABLE_PER_CLASS)?
How does dirty checking work in Hibernate?
Explain @OneToMany with orphanRemoval and cascade types.
What is the difference between @JoinColumn and mappedBy in bidirectional relationships?
How to handle concurrency in JPA (optimistic vs pessimistic locking)?
Explain custom types with @Type or AttributeConverter in JPA.

Microservices with Spring Boot

What are microservices? Advantages/disadvantages over monolithic architecture.
Explain Spring Cloud components: Eureka (service discovery), Ribbon/Feign (client-side load balancing), Hystrix/Resilience4j (circuit breaker).
How do you implement API Gateway in Spring Boot (Spring Cloud Gateway vs Zuul)?
What is distributed tracing? How to use Sleuth and Zipkin?
Explain inter-service communication: Synchronous (REST/Feign) vs Asynchronous (Kafka/RabbitMQ).
How to handle configuration management in microservices (Spring Cloud Config Server)?
What is the Circuit Breaker pattern? Implement with Resilience4j.
Explain Saga pattern for distributed transactions.
How to secure microservices (OAuth2, JWT with Spring Security)?
What are common challenges in microservices (data consistency, logging, monitoring)?

Spring Boot Advanced

Explain Spring Boot Actuator in depth: Custom endpoints, health indicators, metrics with Micrometer/Prometheus.
How does Spring Boot handle externalized configuration (multiple profiles, Config Server)?
What is Spring WebFlux? Difference from traditional Spring MVC (reactive vs blocking).
Explain @Transactional propagation levels and isolation.
How to implement custom auto-configuration in Spring Boot?
What are Spring Boot Starters? How to create a custom starter?
Explain testing in Spring Boot: @SpringBootTest, @WebMvcTest, MockBean.
How to handle global exception handling with @ControllerAdvice and @ExceptionHandler?
What is Spring Data JPA auditing (@CreatedDate, @LastModifiedBy)?
Explain reactive programming with Project Reactor in Spring Boot.

Testing and Best Practices

What are common Java coding best practices (e.g., immutable objects, proper exception handling)?
Explain unit vs integration testing in Java (JUnit, Mockito, Testcontainers).
How do you profile a Java application (VisualVM, JProfiler, async-profiler)?
What is the difference between @Mock and @InjectMocks in Mockito?
Explain Java records, sealed classes, and pattern matching (Java 14+ features).

Data Structures and Algorithms
Array and String Questions
96. Find the two numbers in an array that add up to a given target (Two Sum problem). Explain O(n) solution using HashMap.
97. Merge two sorted arrays into one sorted array without extra space (if possible).
98. Find the longest substring without repeating characters.
99. Rotate an array by k steps (in-place if possible).
100. Find the maximum subarray sum (Kadane's algorithm).
101. Check if a string is a palindrome, ignoring non-alphanumeric characters.
102. Implement string reversal and word reversal in a sentence.
103. Find all duplicates in an array (with constraints like O(1) space).
104. Rearrange positive and negative numbers in an array alternately.
105. Find the missing number in an array of 1 to n.
Linked List Questions
106. Reverse a singly linked list (iterative and recursive).
107. Detect and remove a cycle in a linked list (Floyd's cycle detection).
108. Merge two sorted linked lists.
109. Find the middle of a linked list (one pass).
110. Check if a linked list is a palindrome.
111. Implement LRU Cache using HashMap and Doubly Linked List.
112. Add two numbers represented as linked lists.
113. Flatten a multilevel doubly linked list.
Tree and Binary Search Tree Questions
114. Implement inorder, preorder, postorder traversals (recursive and iterative).
115. Find the height/depth of a binary tree.
116. Check if a binary tree is balanced.
117. Perform level-order (BFS) traversal.
118. Find the lowest common ancestor (LCA) in a binary tree/BST.
119. Serialize and deserialize a binary tree.
120. Validate if a binary tree is a BST.
121. Construct a BST from preorder traversal.
122. Find kth smallest/largest element in a BST.
Heap and Priority Queue Questions
123. Implement a min-heap/max-heap in Java.
124. Find the k largest elements in an array (using PriorityQueue).
125. Merge k sorted arrays/lists.
126. Explain how PriorityQueue works in Java and its use cases.
Graph Questions
127. Implement BFS and DFS on a graph.
128. Detect cycle in an undirected/directed graph.
129. Find shortest path in an unweighted graph (BFS).
130. Implement Dijkstra's algorithm for shortest path.
131. Topological sort in a DAG.
Sorting and Searching Questions
132. Implement QuickSort or MergeSort and explain pivot selection.
133. Binary search variations: Find first/last occurrence, or in rotated sorted array.
134. Explain time complexities of common sorts (Bubble, Insertion, Selection, Merge, Quick, Heap).
Dynamic Programming Questions
135. Fibonacci sequence (memoization vs tabulation).
136. Longest common subsequence/substring.
137. 0/1 Knapsack problem.
138. Coin change problem (minimum coins).
139. Edit distance (Levenshtein distance).
Other Advanced DSA
140. Implement a Trie (prefix tree) for autocomplete.
141. Sliding window technique for maximum in subarray of size k.
142. Design a rate limiter using sliding window or token bucket.
143. Find median from a data stream (using two heaps).
144. Explain hashing collisions and how HashMap handles them in Java.
145. Bit manipulation: Count set bits, find single non-duplicate number.
