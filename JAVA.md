| Concept/Function      | Usage / How to Use                                      | Description / What It Does                                      |
|-----------------------|---------------------------------------------------------|-----------------------------------------------------------------|
| **int[]**             | `int[] array = {1, 2, 3};`                              | Array of primitive integers. Fixed size.                        |
| **Arrays.stream**     | `IntStream stream = Arrays.stream(array);`              | Converts an `int[]` to a stream for functional-style operations.|
| **Collectors**        | `.collect(Collectors.toList())` on a stream             | Collects elements from a stream into a collection like a List or Set. |
| **HashMap**           | `Map<K, V> map = new HashMap<>();`                      | Stores key-value pairs. Fast lookups and inserts.               |
| **HashSet**           | `Set<T> set = new HashSet<>();`                         | Stores unique elements. Used for fast membership checks.        |
| **Map**               | `Map<K, V> map = ...;`                                  | Interface for collections of key-value pairs.                   |
| **Stream.filter**     | `stream.filter(x -> x > 5)`                             | Filters elements of the stream based on a condition.            |
| **Stream.map**        | `stream.map(x -> x * 2)`                                | Applies a function to each element of the stream.               |
| **Stream.reduce**     | `stream.reduce(0, (a, b) -> a + b)`                     | Combines elements of a stream into a single result.             |
| **Arrays.sort**       | `Arrays.sort(array);`                                   | Sorts an array in place.                                        |
| **Collections.sort**  | `Collections.sort(list);`                               | Sorts a List in place.                                          |
| **List.of**           | `List<T> list = List.of(1, 2, 3);`                      | Creates an immutable list of elements.                          |
| **Stream.forEach**    | `stream.forEach(System.out::println);`                  | Performs an action for each element of the stream.              |
| **Optional**          | `Optional<T> optional = ...;`                           | Container object for values that may or may not be present.     |
| **Lambda Expressions**| `(parameters) -> expression` or `(parameters) -> { code block }` | Defines an anonymous function (lambda). Used with streams and functional interfaces. |
| **String.join**       | `String.join(", ", "a", "b", "c");`                     | Joins strings with a delimiter.                                 |
| **StringBuilder**     | `StringBuilder sb = new StringBuilder(); sb.append("text");` | Efficiently builds or modifies strings.                         |
| **Java Generics**     | `List<T> list = new ArrayList<>();`                     | Allows type-safe collections and classes.                       |
| **Exception Handling**| `try { code } catch (Exception e) { handler }`          | Manages errors or exceptional events in a controlled way.       |
| **Java 8 Date/Time API** | `LocalDate.now(); LocalDateTime.now();`              | Modern API for dates and times.                                 |
| **Functional Interfaces** | `@FunctionalInterface` interface with one abstract method | Interfaces suitable for lambda expressions, like `Predicate<T>`, `Function<T, R>`. |
| **Streams.collect**   | `stream.collect(Collectors.groupingBy(...))`            | Collects elements of a stream into a complex structure like a Map. |
