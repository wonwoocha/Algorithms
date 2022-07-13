## Data Structures
- Data structures are an integral part of computers used for the arrangement of data in memory. 
- They are essential and responsible for organizing, processing, accessing, and storing data efficiently. 
- But this is not all. Various types of data structures have their own characteristics, features, applications, advantages, and disadvantages.
- So how do you identify a data structure that is suitable for a particular task? What is meant by the term ‘Data Structure’? 
- How many types of data structures are there and what are they used for?

![image](https://user-images.githubusercontent.com/105867034/178478615-f45c9c89-b567-426a-b291-82235248132f.png)

### Types of Data Structures
- Arrays: An array is a collection of elements of the same type placed in contiguous memory locations.
- Linked Lists: It is a linear data structure, in which the elements are not stored at contiguous memory locations and the elements are linked with each other.
- Stacks: Follow LIFO (Last In First Out) principle. In this, the last element in the stack will be removed first.
- Queues: It follows the FIFO principle (First In First Out), in this, the first element stored is removed first.
- Hash Tables: This is a type of data structure that stores values which have keys related to each of them.
    + Ultimate Objectives of Hashing
        + Minimize Collision
        + Minimize Overflow
        + Minimize Hash Table Size: Keep N(indexes) and/or K(buckets) reasonably small
    + Commonly Used Hash Functions
        + Modulo(Division) Function
        + Digit Folding("hashing")
        + Digit Selection
        + Mid-Square Function

- Trees: It is a data structure in which data is organized hierarchically and linked together. Some Examples are the Binary Search tree, Binary tree, Splay tree, AVL Tree, etc.
    + Differences between B-Tree and T-Tree
        + T-Tree
            + a main-memory data structure
            + a binary tree
            + height-balanced, but not perfectly
            + rebalancing uses tree rotations
        + B-Tree(and B+) Tree
            + an external data structure
            + an m-way tree
            + perfectly height-balanced
            + rebalancing uses node split and merge
            * B-Tree
                * Tree height is taller, because each node can contain fewer keys
                * Has no support for range queries
                * Search may end before reaching the leaf level
            * B+ Tree
                * Tree height is smaller, because each node can contain more keys
                * Has support for range queries
                * Search must continue to the leaf level

    + Degree of Trees
        + Unary Tree: linked list
        + Binary Tree: binary search tree
        + m-way Tree(m>2)
    + Height Balance
        + Unbalanced
        + Balanced (but not perfectly): AVL tree, T-tree
        + Perfectly Balanced: 2-3 tree
    + Dimension
        + One Dimension: AVL tree, T-tree
        + n-dimention(n>=2): quad tree, kd tree
    
- Heaps: It is a specialized tree-based data structure, also called binary heap in which data is stored.
- Graphs: It consists of a set of nodes and edges connecting each other.
    + Topics
        + Graph Representaion: Adjacency Matrix/Lists
        + Graph Traversal: DFS, BFS
        + Spanning Tree: A Tree of N Nodes and N-1 edges, Cycles are removed from the graph
        + Minimum Spanning Tree: A spanning tree with a minimum total weight of all the edges
        + Minimum Spanning Tree Algorithm
            + Prim's algorithm / Kruskal's algorithm / Dijkstra's algorithm / Warshall's algorithm
        + Transitive Closure Algorithms

## Algorithm
<img src=https://user-images.githubusercontent.com/105867034/178479808-21ab10ae-2842-4e71-8f65-8e64fee8a340.png width=600px height=350px></img>

### Characteristics of Algorithm
- Clear and Unambiguous: The algorithm should be clear and unambiguous. Each of its steps should be clear in all aspects and must lead to only one meaning.
- Well-Defined Inputs: If an algorithm says to take inputs, it should be well-defined inputs. 
- Well-Defined Outputs: The algorithm must clearly define what output will be yielded and it should be well-defined as well. 
- Finite-ness: The algorithm must be finite, i.e. it should terminate after a finite time.
- Feasible: The algorithm must be simple, generic, and practical, such that it can be executed with the available resources. It must not contain some future technology or anything.
- Language Independent: The Algorithm designed must be language-independent, i.e. it must be just plain instructions that can be implemented in any language, and yet the output will be the same, as expected.

### Types of Algorithm
1. Brute Force Algorithm             
2. Recursive Algorithm        
3. Backtracking Algorithm         
4. Searching Algorithm         
5. Sorting Algorithm         
6. Hashing Algorithm         
7. Divide and Conquer Algorithm          
8. Greedy Algorithm        
9. Dynamic Programming Algorithm         
10. Randomized Algorithm           
