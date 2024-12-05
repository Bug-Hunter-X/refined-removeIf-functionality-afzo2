# Kotlin Collection removeIf() Behavior

This example demonstrates the behavior of the `removeIf()` function when used with different Kotlin collection types (Lists, Sets, and Maps). While seemingly straightforward, there are subtle differences to be aware of in how `removeIf()` modifies these collections.

**Key Observation:** The `removeIf()` function modifies the original collection in place.

**Files:**

- `bug.kt`: Demonstrates the `removeIf()` usage and its outcome for each collection type. 
- `bugSolution.kt`: (Not applicable for this example; the bug is in understanding the behavior, not fixing a broken function.)

**Learning Points:**

- Understand how `removeIf()` handles iteration and element removal within Lists, Sets, and Maps. Note that the iteration order is important.
- Pay close attention to the result when working with mutable collections and functions that modify them directly.
- Always test thoroughly across different collection types to avoid unexpected behaviors.