## Experiment 4: Study of Set in Python

### Aim

To understand and implement the `set` and `frozenset` data structures in Python, exploring their unique properties and performing various set operations.

### Theory

* **Definition:** A set is an unordered collection of items where every element is unique (no duplicates) and must be immutable.
* **Unordered Nature:** Since sets are unordered, the items do not have a defined index, and their order may change every time they are accessed.
* **Mutability:** Standard sets are mutable, meaning elements can be added or removed using methods like `.add()` and `.remove()`.
* **Frozenset:** A `frozenset` is an immutable version of a set; once created, its elements cannot be modified.
* **Set Operations:** Python supports standard mathematical set operations such as Union (), Intersection (), Difference (), and Symmetric Difference ().

### Algorithm

1. **Initialization:** Create a set using curly braces `{}` or the `set()` constructor.
2. **Duplicate Handling:** Observe that duplicate entries are automatically removed during initialization.
3. **Modification:** Use `.add(element)` to insert a new item and `.remove(element)` to delete an existing one.
4. **Mathematical Operations:**
* Apply the pipe operator (`|`) for Union.
* Apply the ampersand (`&`) for Intersection.
* Apply the minus sign (`-`) for Difference.
* Apply the caret (`^`) for Symmetric Difference.


5. **Immutability:** Define a `frozenset()` to prevent further changes to the collection.
6. **Output:** Print the results of each operation to verify the logic.

---

