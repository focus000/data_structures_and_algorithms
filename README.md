# data_structures_and_algorithms

## Plan

![Plan](Plan.jpg)

## Complexity Analysis

### Big-Oh

$T(n) = O(f(n))$ iff $\exist c, n_0$ s.t.
$$T(n) \leq c f(n) \quad \forall n > n_0$$

### Omega

$T(n) = \Omega(f(n))$ iff $\exist c, n_0$ s.t.
$$T(n) \geq c f(n) \quad \forall n > n_0$$

### Theta

$T(n) = \theta(f(n))$ iff $\exist c_1, c_2, n_0$ s.t.
$$c_1 f(n) \leq T(n) \leq c_2 f(n) \quad \forall n > n_0$$

### Little-Oh

$T(n) = o(f(n))$ iff $\forall c > 0, \exist n_0$ s.t.
$$T(n) \leq c f(n) \quad \forall n > n_0$$

## Linear List

![Linear List](LinearList/LinearList.jpg)
![nonlinear List](LinearList/nonLinearList.jpg)

### Array

数组（Array）是一种线性表数据结构。它用一组连续的内存空间，来存储一组具有相同类型的数据。

![Array](LinearList/Array.jpg)

寻址公式：

```cpp
a[i]_address = base_address + i * data_type_size
```

特性：

- 下标随机访问 $O(1)$
- 插入删除 $O(n)$

### Linked List

链表（Linked List）用指针将离散的内存空间串联起来

![SinglyLinkedList](LinearList/SinglyLinkedList.jpg)
![CircylarLinkedLists](LinearList/CircylarLinkedLists.jpg)
![DoubleLinkedLists](LinearList/DoubleLinkedLists.jpg)
![DoubleCircularLinkedList](LinearList/DoubleCircularLinkedList.jpg)

与数组比较：

![ArrayLinkedList_1](LinearList/ArrayLinkedList_1.jpg)
![ArrayLinkedList_2](LinearList/ArrayLinkedList_2.jpg)
