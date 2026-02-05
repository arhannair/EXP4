## Experiment 4: Study of Set in Python

### Aim

To understand and implement the `set` and `frozenset` data structures in Python, exploring their unique properties and performing various set operations.

### Theory

* **Definition**: A set is an unordered collection of items where every element is unique and must be immutable.
* **Unordered Nature**: Sets do not maintain the order of elements, meaning items do not have a defined index.
* **Duplicate Handling**: Sets automatically remove duplicate values upon creation or when adding new items.
* **Mutability**: Standard sets are mutable, allowing for the addition and removal of elements.
* **Frozenset**: A `frozenset` is an immutable version of a set that cannot be changed after it is defined.
* **Set Operations**: Python supports mathematical operations including Union (), Intersection (), Difference (), and Symmetric Difference ().

### Algorithm

1. **Initialize** a set using curly braces `{}` or by casting a list using the `set()` constructor.
2. **Add or Remove** elements using the `.add()`, `.remove()`, or `.discard()` methods.
3. **Perform Set Algebra** using operators like `|` (union), `&` (intersection), `-` (difference), and `^` (symmetric difference).
4. **Create a Frozenset** to demonstrate a collection that remains constant and cannot be modified.
5. **Display** results to observe how sets handle unique data and unordered output.

### Conclusion

Through this experiment, I successfully implemented Python sets to manage unique data collections. I observed that sets are highly efficient for removing duplicates from lists and performing complex relational logic, such as finding common subjects among students or identifying absent students by calculating the difference between two sets. The experiment also highlighted the functional difference between mutable sets and immutable frozensets.

---
