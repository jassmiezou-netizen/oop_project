# Task 2: Self-study on a New Data Structure and Algorithm - Heap and Heap Sort
## 1. Overview
We chose **Binary Heap** (data structure) and **Heap Sort** (algorithm) because they are not covered in the course. We implemented a max heap and will implement heap sort later.

## 2. Data Structure: Binary Heap
- **ADT**: A binary heap is a complete binary tree. In a max heap, parent nodes are larger than children. Main operations: build heap, heapify, get root, insert, extract root.
- **Applications**: Priority queues, task scheduling, Dijkstra's algorithm.

## 3. Algorithm: Heap Sort
- **Idea**: Build a max heap, then repeatedly swap the root (largest) with the last element, reduce heap size, and heapify the root. This sorts the array in place.
- **Time Complexity**: O(n log n) for all cases. Space: O(1).

## 4. Code Implementation
### File: `heap.py`
- `Heap` class: base class with `__init__`, `build_heap`, `heapify` (placeholder), and helper methods.
- `Max_Heap` class: inherits `Heap` and implements `heapify` for max heap.
- `Min_Heap` not yet implemented.

### How to Run
```python
from heap import Max_Heap
data = [1, 4, 3, 7, 8, 3, 6, 2, 7, 10]
maxheap = Max_Heap(data)
print(maxheap.data)  # Example output: [10, 8, 6, 7, 4, 3, 3, 2, 7, 1]

##Preliminary Results

##Future Work
##References

    