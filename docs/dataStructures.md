---
id: dataStructures
title: Data Structures
sidebar_label: Data Structures
---

## Doubly Linked List

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/doubly_linked_list.js)

#### new DoublyLinkedList() 

Class for Doubly Linked List






##### Returns


- `Void`



#### DoublyLinkedList.length() 

Get length of Doubly Linked List






##### Returns


- `Number`  Length of Linked List



#### DoublyLinkedList.isEmpty() 

Check if Doubly Linked List is empty or not






##### Returns


- `Boolean`  `true` if empty else `false`



#### DoublyLinkedList.tail() 

Get tail of Doubly Linked List






##### Returns


- `Node`  Tail node



#### DoublyLinkedList.head() 

Get head of Doubly Linked List






##### Returns


- `Node`  Head node



#### DoublyLinkedList.push(data) 

Pushes node to the head of Doubly Linked List




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data |  | Data or value contained in Node | &nbsp; |




##### Returns


- `None`  



#### DoublyLinkedList.insertAfter(prevNode, data) 

Inserts node after a given node




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| prevNode | `Node`  | Node after which insertion needs to take place | &nbsp; |
| data |  | Data or value contained in Node | &nbsp; |




##### Returns


- `None`  



#### DoublyLinkedList.insertBefore(node, data) 

Inserts node before a given node




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| node | `Node`  | Node before which insertion needs to take place | &nbsp; |
| data |  | Data or value contained in Node | &nbsp; |




##### Returns


- `Node`  



#### DoublyLinkedList.pop() 

Pop node from the head






##### Returns


- `Node`  Node popped



#### DoublyLinkedList.deleteNode(node) 

Delete node from the list




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| node | `Node`  | Node to be deleted | &nbsp; |




##### Returns


- `None`  



#### DoublyLinkedList.getNode(index) 

Returns node at given index




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index of required node | &nbsp; |




##### Returns


- `Node`  Required node



#### DoublyLinkedList.toString() 

Returns string representing the Doubly Linked List






##### Returns


- `String`  String representation of Doubly Linked List




## Fenwick Tree


[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/fenwick_tree.js)

#### new FenwickTree() 

Class for Fenwick Tree






##### Returns


- `Void`



#### this._list()  *private method*








##### Returns


- `Void`



#### this._length()  *private method*








##### Returns


- `Void`



#### size() 

Get size of Fenwick Tree






##### Returns


- `Number`  Size of Fenwick Tree



#### buildTree(array) 

Builds Fenwick Tree




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| array | `Array`  | Array elements to be used to build the tree | &nbsp; |




##### Returns


- `None`  



#### isEmpty() 

Check if tree is empty






##### Returns


- `Boolean`  Returns true if empty else false



#### getSum(index) 

Gets prefix sum of the array using the tree




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index till which sum needs to be calculated | &nbsp; |




##### Returns


- `Number`  Prefix sum



#### updateTree(index, element) 

Updates the tree with adding element to given index




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index of element to be updated | &nbsp; |
| element | `Number`  | Element to be added | &nbsp; |




##### Returns


- `None`  



#### rangeSum(left, right) 

Calculates range sum from given index to given index




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| left | `Number`  | Left index | &nbsp; |
| right | `Number`  | Right index | &nbsp; |




##### Returns


- `Number`  Range sum




## Graph

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/graph.js)


#### new Graph() 

Class for Graphs






##### Returns


- `Void`



#### this._isDirected()  *private method*








##### Returns


- `Void`



#### this._vertices()  *private method*








##### Returns


- `Void`



#### this._edges()  *private method*








##### Returns


- `Void`



#### size() 

Get size of graph






##### Returns


- `Number`  Size of graph



#### vertices() 

Get vertices of graph






##### Returns


- `Array`  Vertices in the graph



#### isEmpty() 

Check whether graph is empty or not






##### Returns


- `Boolean`  True if empty else False



#### addVertex(vertex) 

Adds vertex to the Graph




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertex | `Number`  | Vertex label | &nbsp; |




##### Returns


- `Void`



#### addEdge(vertexA, vertexB, weight) 

Adds edge between two vertices




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertexA | `Number`  | Starting vertex label | &nbsp; |
| vertexB | `Number`  | Ending vertex label | &nbsp; |
| weight | `Number`  | Weight to be added for edge | &nbsp; |




##### Returns


- `Void`



#### removeVertex(vertex) 

Removes vertex from the Graph




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertex | `Number`  | Vertex label | &nbsp; |




##### Returns


- `Void`



#### removeEdge(vertexA, vertexB) 

Removes edge between two vertices




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertexA | `Number`  | Starting vertex label | &nbsp; |
| vertexB | `Number`  | Ending vertex label | &nbsp; |




##### Returns


- `Void`



#### isNeighbour(vertexA, vertexB) 

Check whether one vertex is neighbour to another




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertexA | `Number`  | Origin vertex | &nbsp; |
| vertexB | `Number`  | Vertex to be checked for | &nbsp; |




##### Returns


- `Boolean`  True if neighbour else False



#### getNeighbours(vertex) 

Returns neighbours of a given vertex




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertex | `Number`  | Vertex whose neighbours are required | &nbsp; |




##### Returns


- `Array`  List of neighbouring vertices



#### getEdgeWeight(vertexA, vertexB) 

Returns edge weight of edge between two vertices




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| vertexA | `Number`  | Starting Vertex label | &nbsp; |
| vertexB | `Number`  | Ending Vertex label | &nbsp; |




##### Returns


- `Number`  Edge weight



#### dfs(root, callback) 

Depth First Search




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| root | `Number`  | Root vertex | &nbsp; |
| callback | `Function`  | Function to be called on each vertex | &nbsp; |




##### Returns


- `Void`



#### bfs(root, callback) 

Breadth First Search




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| root | `Number`  | Root vertex | &nbsp; |
| callback | `Function`  | Function to be called on each vertex | &nbsp; |




##### Returns


- `Void`




## Heap

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/heap.js)

#### new Heap() 

Class for Heaps






##### Returns


- `Void`



#### this._list()  *private method*








##### Returns


- `Void`



#### this._length()  *private method*








##### Returns


- `Void`



#### this._compareFunc()  *private method*








##### Returns


- `Void`



#### size() 

Get size of Heap






##### Returns


- `Number`  Size of Heap



#### _buildHeap(data)  *private method*

Build Heap




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data |  | Single element or array of data to be used for Heap | &nbsp; |




##### Returns


- `None`  



#### _parent(index)  *private method*

Get parent of index




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index for which parent is required | &nbsp; |




##### Returns


- `Number`  Parent of index



#### _left(index)  *private method*

Get index of left node




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index for which left node index is needed | &nbsp; |




##### Returns


- `Number`  Index of left node



#### _right(index)  *private method*

Get index of right node




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index for which right node index is needed | &nbsp; |




##### Returns


- `Number`  Index of right node



#### _swap(x, y)  *private method*

Swap nodes




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| x | `Number`  | Index of node one | &nbsp; |
| y | `Number`  | Index of node two | &nbsp; |




##### Returns


- `None`  



#### _heapify(index)  *private method*

Heapifies the array




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index of root | &nbsp; |




##### Returns


- `None`  



#### isEmpty() 

Whether Heap is empty






##### Returns


- `Boolean`  Whether Heap is empty or not



#### top() 

Get top of Heap






##### Returns


-  Top value of Heap



#### push(element) 

Pushes node to the Heap




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| element |  | Value to be inserted | &nbsp; |




##### Returns


- `None`  



#### pop() 

Pop node from the Heap






##### Returns


-  Top popped node from the Heap




## Linked List

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/linked_list.js)

#### new LinkedList() 

Class for Linked List






##### Returns


- `Void`



#### this._head()  *private method*








##### Returns


- `Void`



#### this._length()  *private method*








##### Returns


- `Void`



#### length() 

Get length of Linked List






##### Returns


- `Number`  Length of Linked List



#### isEmpty() 

Check if Linked List is empty or not






##### Returns


- `Boolean`  `true` if empty else `false`



#### push(data) 

Pushes node to the end of Linked List




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data |  | Data or value contained in Node | &nbsp; |




##### Returns


- `LinkedList`  `this`



#### pop() 

Pops node from the end of Linked List






##### Returns


- `LinkedList`  `this`



#### popNodeByIndex(index) 

Pops node from particular place in Linked List




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index of node from end of the list | &nbsp; |




##### Returns


- `LinkedList`  `this`



#### getNodeByIndex(index) 

Returns node at particular index else throws error if index out of range




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| index | `Number`  | Index of node from end | &nbsp; |




##### Returns


- `Node`  Required node



#### getNodeByValue(value) 

Returns first occurance of node with given value




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| value |  | Value to be searched | &nbsp; |




##### Returns


- `Node`  First occurance of node with given value else -1



#### getListAsArray() 

Returns Linked List as Array






##### Returns


- `Array`  Array containing values of Linked List



#### reverseList() 

Reverses Linked List






##### Returns


-  None



#### forEach(func) 

Iterates over all nodes of linked list and runs function on the node value




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| func | `func`  | Function containing logic to be applied to node value | &nbsp; |




##### Returns


- `None`  



#### toString() 

Returns string representing the linked list






##### Returns


- `string`  String representation of linked list




## Queue

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/queue.js)

#### new Queue() 

Class for Queues






##### Returns


- `Void`



#### this._list()  *private method*








##### Returns


- `Void`



#### size() 

Get length of Queue






##### Returns


- `Number`  Size of Queue



#### isEmpty() 

Check if Queue is empty or not






##### Returns


- `Boolean`  `true` if empty else `false`



#### push(data) 

Pushes node in Queue




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data |  | Data or value to be pushed | &nbsp; |




##### Returns


- `None`  



#### pop() 

Pop node from Queue






##### Returns


-  Value of node which was popped



#### front() 

Get front value on Queue






##### Returns


-  Value of node at the front



#### back() 

Get back value on Queue






##### Returns


-  Value of node at the back




## Stack

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/stack.js)

#### new Stack() 

Class for Stacks






##### Returns


- `Void`



#### this._list()  *private method*








##### Returns


- `Void`



#### size() 

Get length of Stack






##### Returns


- `Number`  Size of Stack



#### isEmpty() 

Check if Stack is empty or not






##### Returns


- `Boolean`  `true` if empty else `false`



#### push(data) 

Pushes node in Stack




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data |  | Data or value to be pushed | &nbsp; |




##### Returns


- `None`  



#### pop() 

Pop node from Stack






##### Returns


-  Value of node which was popped



#### top() 

Get top value on stack






##### Returns


-  Value of node at the top




## Trie

[Code](https://github.com/manrajgrover/algorithms-js/tree/master/src/data-structures/trie.js)

#### new Trie() 

Class for Trie






##### Returns


- `Void`



#### this._root()  *private method*








##### Returns


- `Void`



#### this._size()  *private method*








##### Returns


- `Void`



#### size() 

Get size of Trie






##### Returns


- `Number`  Size of Trie



#### isEmpty() 

Checks if trie is empty or not






##### Returns


- `Boolean`  true if empty else false



#### insert(data, val) 

Inserts data into trie




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data | `String`  | String to be inserted | &nbsp; |
| val |  | Leaf node value | &nbsp; |




##### Returns


- `Node`  Inserted node in trie



#### search(data) 

Searches and returns whether word exists in trie




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data | `String`  | Data to be searched | &nbsp; |




##### Returns


-  val of leaf node, if exist else false



#### _remove(node, data, level, length)  *private method*

Recursively deletes word from the trie




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| node | `Node`  | Current node being explored | &nbsp; |
| data | `String`  | Word to be deleted | &nbsp; |
| level | `Integer`  | Depth looked in trie | &nbsp; |
| length | `Integer`  | Length of word | &nbsp; |




##### Returns


- `Boolean`  true if deleted else false



#### delete(data)  *private method*

Word to be deleted




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data | `String`  | Word to be deleted | &nbsp; |




##### Returns


- `Boolean`  true if deleted else false
