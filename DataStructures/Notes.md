This is a list of [data structures](https://en.wikipedia.org/wiki/Data_structure). For a wider list of terms, see [

list of terms relating to algorithms and data structures](https://en.wikipedia.org/wiki/List_of_terms_relating_to_algorithms_and_data_structures). For a comparison of running 

time a subset of this list 

see [comparison of data structures](https://en.wikipedia.org/wiki/Comparison_of_data_structures).

### Contents

- [1Data types](https://en.wikipedia.org/wiki/List_of_data_structures#Data_types)
    - [1.1Primitive types](https://en.wikipedia.org/wiki/List_of_data_structures#Primitive_types)
    - [1.2Composite types or non-primitive type](https://en.wikipedia.org/wiki/List_of_data_structures#Composite_types_or_non-primitive_type)
    - [1.3Abstract data types](https://en.wikipedia.org/wiki/List_of_data_structures#Abstract_data_types)

- [2Linear data structures](https://en.wikipedia.org/wiki/List_of_data_structures#Linear_data_structures)
    - [2.1Arrays](https://en.wikipedia.org/wiki/List_of_data_structures#Arrays)
    - [2.2Lists](https://en.wikipedia.org/wiki/List_of_data_structures#Lists)

- [3Trees](https://en.wikipedia.org/wiki/List_of_data_structures#Trees)
    - [3.1Binary trees](https://en.wikipedia.org/wiki/List_of_data_structures#Binary_trees)
    - [3.2B-trees](https://en.wikipedia.org/wiki/List_of_data_structures#B-trees)
    - [3.3Heaps](https://en.wikipedia.org/wiki/List_of_data_structures#Heaps)
    - [3.4Trees](https://en.wikipedia.org/wiki/List_of_data_structures#Trees_2)
    - [3.5Multiway trees](https://en.wikipedia.org/wiki/List_of_data_structures#Multiway_trees)
    - [3.6Space-partitioning trees](https://en.wikipedia.org/wiki/List_of_data_structures#Space-partitioning_trees)
    - [3.7Application-specific trees](https://en.wikipedia.org/wiki/List_of_data_structures#Application-specific_trees)

- [4Hash-based structures](https://en.wikipedia.org/wiki/List_of_data_structures#Hash-based_structures)
- [5Graphs](https://en.wikipedia.org/wiki/List_of_data_structures#Graphs)
- [6Other](https://en.wikipedia.org/wiki/List_of_data_structures#Other)
- [7See also](https://en.wikipedia.org/wiki/List_of_data_structures#See_also)
- [8External links](https://en.wikipedia.org/wiki/List_of_data_structures#External_links)

### Data types[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=1)]

#### [Primitive types](https://en.wikipedia.org/wiki/Primitive_type)[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=2)]

- [Boolean](https://en.wikipedia.org/wiki/Boolean_data_type), true or false.
- [Character](https://en.wikipedia.org/wiki/Character_(computing))
- [Floating-point](https://en.wikipedia.org/wiki/Floating_point) numbers, limited precision approximations of [real number](https://en.wikipedia.org/wiki/Real_number) values.
    - Including [Single precision](https://en.wikipedia.org/wiki/Single_precision) and [Double precision](https://en.wikipedia.org/wiki/Double_precision) [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) Floats, among [others](https://en.wikipedia.org/wiki/Category:Floating_point_types)

- [Fixed-point numbers](https://en.wikipedia.org/wiki/Fixed-point_arithmetic)
- [Integer](https://en.wikipedia.org/wiki/Integer_(computer_science)), integral or fixed-precision values.
- [Reference](https://en.wikipedia.org/wiki/Reference_(computer_science)) (also called a pointer or handle), a small value referring to another object's address in memory, possibly a much larger one.
- [Enumerated type](https://en.wikipedia.org/wiki/Enumerated_type), a small set of uniquely named values.

#### [Composite types](https://en.wikipedia.org/wiki/Composite_type) or non-primitive type[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=3)]

- [Array](https://en.wikipedia.org/wiki/Array_data_structure) (as an example [String](https://en.wikipedia.org/wiki/String_(computer_science)) which is an array of characters)
- [Record](https://en.wikipedia.org/wiki/Record_(computer_science)) (also called [tuple](https://en.wikipedia.org/wiki/Tuple) or [structure](https://en.wikipedia.org/wiki/Struct_(C_programming_language)))
- [Union](https://en.wikipedia.org/wiki/Union_(computer_science)) ([Tagged union](https://en.wikipedia.org/wiki/Tagged_union) is a subset, also called [variant](https://en.wikipedia.org/wiki/Variant_type), variant record, discriminated union, or disjoint union)

#### [Abstract data types](https://en.wikipedia.org/wiki/Abstract_data_types)[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=4)]

- [Container](https://en.wikipedia.org/wiki/Container_(data_structure))
- [List](https://en.wikipedia.org/wiki/List_(abstract_data_type))
- [Tuple](https://en.wikipedia.org/wiki/Tuple)
- [Multimap](https://en.wikipedia.org/wiki/Multimap) (example [Associative array](https://en.wikipedia.org/wiki/Associative_array))
- [Set](https://en.wikipedia.org/wiki/Set_(computer_science))
- [Multiset (bag)](https://en.wikipedia.org/wiki/Multiset_(abstract_data_type))
- [Stack](https://en.wikipedia.org/wiki/Stack_(data_structure))
- [Queue](https://en.wikipedia.org/wiki/Queue_(data_structure)) (example [Priority queue](https://en.wikipedia.org/wiki/Priority_queue))
- [Double-ended queue](https://en.wikipedia.org/wiki/Double-ended_queue)
- [Graph](https://en.wikipedia.org/wiki/Graph_(data_structure)) (example [Tree](https://en.wikipedia.org/wiki/Tree_(computer_science)), [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure)))

Some properties of abstract data types:

StructureOrderUnique

 [List](https://en.wikipedia.org/wiki/List_(abstract_data_type)) yes no

 [Associative array](https://en.wikipedia.org/wiki/Associative_array) no yes

 [Set](https://en.wikipedia.org/wiki/Set_(computer_science)) no yes

 [Multiset (bag)](https://en.wikipedia.org/wiki/Multiset_(abstract_data_type)) no no

Order means the insertion sequence counts. Unique means that duplicate elements are not allowed, based on some inbuilt or, alternatively, user-defined rule for comparing elements.

### Linear data structures[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=5)]

A data structure is said to be linear if its elements form a sequence.

#### Arrays[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=6)]

- [Array](https://en.wikipedia.org/wiki/Array_data_structure)
- [Bit array](https://en.wikipedia.org/wiki/Bit_array)
- [Bit field](https://en.wikipedia.org/wiki/Bit_field)
- [Bitboard](https://en.wikipedia.org/wiki/Bitboard)
- [Bitmap](https://en.wikipedia.org/wiki/Bitmap)
- [Circular buffer](https://en.wikipedia.org/wiki/Circular_buffer)
- [Control table](https://en.wikipedia.org/wiki/Control_table)
- [Image](https://en.wikipedia.org/wiki/System_image)
- [Dope vector](https://en.wikipedia.org/wiki/Dope_vector)
- [Dynamic array](https://en.wikipedia.org/wiki/Dynamic_array)
- [Gap buffer](https://en.wikipedia.org/wiki/Gap_buffer)
- [Hashed array tree](https://en.wikipedia.org/wiki/Hashed_array_tree)
- [Heightmap](https://en.wikipedia.org/wiki/Heightmap)
- [Lookup table](https://en.wikipedia.org/wiki/Lookup_table)
- [Matrix](https://en.wikipedia.org/wiki/Matrix_(computer_science))
- [Parallel array](https://en.wikipedia.org/wiki/Parallel_array)
- [Sorted array](https://en.wikipedia.org/wiki/Sorted_array)
- [Sparse matrix](https://en.wikipedia.org/wiki/Sparse_matrix)
- [Iliffe vector](https://en.wikipedia.org/wiki/Iliffe_vector)
- [Variable-length array](https://en.wikipedia.org/wiki/Variable-length_array)

#### Lists[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=7)]

- [Doubly linked list](https://en.wikipedia.org/wiki/Doubly_linked_list)
- [Array list](https://en.wikipedia.org/wiki/Array_list)
- [Linked list](https://en.wikipedia.org/wiki/Linked_list)
- [Self-organizing list](https://en.wikipedia.org/wiki/Self-organizing_list)
- [Skip list](https://en.wikipedia.org/wiki/Skip_list)
- [Unrolled linked list](https://en.wikipedia.org/wiki/Unrolled_linked_list)
- [VList](https://en.wikipedia.org/w/index.php?title=VList&action=edit&redlink=1)
- [Conc-tree list](https://en.wikipedia.org/wiki/Conc-tree_list)
- [Xor linked list](https://en.wikipedia.org/wiki/Xor_linked_list)
- [Zipper](https://en.wikipedia.org/wiki/Zipper_(data_structure))
- [Doubly connected edge list](https://en.wikipedia.org/wiki/Doubly_connected_edge_list) also known as half-edge
- [Difference list](https://en.wikipedia.org/wiki/Difference_list)
- [Free list](https://en.wikipedia.org/wiki/Free_list)

### Trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=8)]

Main article: [Tree (data structure)](https://en.wikipedia.org/wiki/Tree_(data_structure))

#### Binary trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=9)]

- [AA tree](https://en.wikipedia.org/wiki/AA_tree)
- [AVL tree](https://en.wikipedia.org/wiki/AVL_tree)
- [Binary search tree](https://en.wikipedia.org/wiki/Binary_search_tree)
- [Binary tree](https://en.wikipedia.org/wiki/Binary_tree)
- [Cartesian tree](https://en.wikipedia.org/wiki/Cartesian_tree)
- [Left-child right-sibling binary tree](https://en.wikipedia.org/wiki/Left-child_right-sibling_binary_tree)
- [Order statistic tree](https://en.wikipedia.org/wiki/Order_statistic_tree)
- [Pagoda](https://en.wikipedia.org/wiki/Pagoda_(data_structure))
- [Randomized binary search tree](https://en.wikipedia.org/wiki/Randomized_binary_search_tree)
- [Red–black tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
- [Rope](https://en.wikipedia.org/wiki/Rope_(computer_science))
- [Scapegoat tree](https://en.wikipedia.org/wiki/Scapegoat_tree)
- [Self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)
- [Splay tree](https://en.wikipedia.org/wiki/Splay_tree)
- [T-tree](https://en.wikipedia.org/wiki/T-tree)
- [Tango tree](https://en.wikipedia.org/wiki/Tango_tree)
- [Threaded binary tree](https://en.wikipedia.org/wiki/Threaded_binary_tree)
- [Top tree](https://en.wikipedia.org/wiki/Top_tree)
- [Treap](https://en.wikipedia.org/wiki/Treap)
- [WAVL tree](https://en.wikipedia.org/wiki/WAVL_tree)
- [Weight-balanced tree](https://en.wikipedia.org/wiki/Weight-balanced_tree)

#### B-trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=10)]

- [B-tree](https://en.wikipedia.org/wiki/B-tree)
- [B+ tree](https://en.wikipedia.org/wiki/B%2B_tree)
- [B*-tree](https://en.wikipedia.org/wiki/B*-tree)
- [B sharp tree](https://en.wikipedia.org/w/index.php?title=B_sharp_tree&action=edit&redlink=1)
- [Dancing tree](https://en.wikipedia.org/wiki/Dancing_tree)
- [2-3 tree](https://en.wikipedia.org/wiki/2-3_tree)
- [2-3-4 tree](https://en.wikipedia.org/wiki/2-3-4_tree)
- [

Queap](https://en.wikipedia.org/wiki/Queap)
- [Fusion tree](https://en.wikipedia.org/wiki/Fusion_tree)
- [Bx-tree](https://en.wikipedia.org/wiki/Bx-tree_Moving_Object_Index)
- [AList](https://en.wikipedia.org/w/index.php?title=AList&action=edit&redlink=1)

#### Heaps[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=11)]

- [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure))
- [Binary 

heap](https://en.wikipedia.org/wiki/Binary_heap)
- [B-heap](https://en.wikipedia.org/wiki/B-heap)
- [Weak heap](https://en.wikipedia.org/wiki/Weak_heap)
- [Binomial heap](https://en.wikipedia.org/wiki/Binomial_heap)
- [Fibonacci heap](https://en.wikipedia.org/wiki/Fibonacci_heap)
- [AF-heap](https://en.wikipedia.org/wiki/AF-heap)
- [Leonardo Heap](https://en.wikipedia.org/wiki/Smoothsort)
- [2-3 heap](https://en.wikipedia.org/wiki/2-3_heap)
- [Soft 

heap](https://en.wikipedia.org/wiki/Soft_heap)
- [Pairing heap](https://en.wikipedia.org/wiki/Pairing_heap)
- [Leftist heap](https://en.wikipedia.org/wiki/Leftist_tree)
- [Treap](https://en.wikipedia.org/wiki/Treap)
- [

Beap](https://en.wikipedia.org/wiki/Beap)
- [Skew heap](https://en.wikipedia.org/wiki/Skew_heap)
- [Ternary heap](https://en.wikipedia.org/wiki/Ternary_heap)
- [D-ary heap](https://en.wikipedia.org/wiki/D-ary_heap)
- [

Brodal queue](https://en.wikipedia.org/wiki/Brodal_queue)

#### Trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=12)]

In these data structures each tree node compares a bit slice of key values.

- [Tree_(data_structure)](https://en.wikipedia.org/wiki/Tree_(data_structure))
- [Radix tree](https://en.wikipedia.org/wiki/Radix_tree)
- [Suffix tree](https://en.wikipedia.org/wiki/Suffix_tree)
- [Suffix array](https://en.wikipedia.org/wiki/Suffix_array)
- [Compressed suffix array](https://en.wikipedia.org/wiki/Compressed_suffix_array)
- [FM-index](https://en.wikipedia.org/wiki/FM-index)
- [Generalised suffix tree](https://en.wikipedia.org/wiki/Generalised_suffix_tree)
- [B-tree](https://en.wikipedia.org/wiki/B-tree)
- [Judy array](https://en.wikipedia.org/wiki/Judy_array)
- [X-fast tree](https://en.wikipedia.org/w/index.php?title=X-fast_tree&action=edit&redlink=1)
- [Y-fast tree](https://en.wikipedia.org/w/index.php?title=Y-fast_tree&action=edit&redlink=1)
- [Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree)
- [Ctree](https://en.wikipedia.org/w/index.php?title=Ctree&action=edit&redlink=1)

#### Multiway trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=13)]

- [Ternary tree](https://en.wikipedia.org/wiki/Ternary_tree)
- [K-ary tree](https://en.wikipedia.org/wiki/K-ary_tree)
- [And–or tree](https://en.wikipedia.org/wiki/And%E2%80%93or_tree)
- [(a,b)-tree](https://en.wikipedia.org/wiki/(a,b)-tree)
- [Link/cut tree](https://en.wikipedia.org/wiki/Link/cut_tree)
- [SPQR-tree](https://en.wikipedia.org/wiki/SPQR-tree)
- [Spaghetti stack](https://en.wikipedia.org/wiki/Spaghetti_stack)
- [Disjoint-set data structure](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)
- [Fusion tree](https://en.wikipedia.org/wiki/Fusion_tree)
- [Enfilade](https://en.wikipedia.org/wiki/Enfilade_(Xanadu))
- [Exponential tree](https://en.wikipedia.org/wiki/Exponential_tree)
- [Fenwick tree](https://en.wikipedia.org/wiki/Fenwick_tree)
- [Van Emde Boas tree](https://en.wikipedia.org/wiki/Van_Emde_Boas_tree)
- [Rose tree](https://en.wikipedia.org/wiki/Rose_tree)

#### Space-partitioning trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=14)]

These are data structures used for [space partitioning](https://en.wikipedia.org/wiki/Space_partitioning) or [binary space partitioning](https://en.wikipedia.org/wiki/Binary_space_partitioning).

- [Segment tree](https://en.wikipedia.org/wiki/Segment_tree)
- [Interval tree](https://en.wikipedia.org/wiki/Interval_tree)
- [Range tree](https://en.wikipedia.org/wiki/Range_tree)
- [Bin](https://en.wikipedia.org/wiki/Bin_(computational_geometry))
- [K-d tree](https://en.wikipedia.org/wiki/K-d_tree)
- [Implicit k-d tree](https://en.wikipedia.org/wiki/Implicit_k-d_tree)
- [Min/max k-d tree](https://en.wikipedia.org/wiki/Min/max_kd-tree)
- [Relaxed k-d tree](https://en.wikipedia.org/wiki/Relaxed_k-d_tree)
- [Adaptive k-d tree](https://en.wikipedia.org/wiki/Adaptive_k-d_tree)
- [Quadtree](https://en.wikipedia.org/wiki/Quadtree)
- [Octree](https://en.wikipedia.org/wiki/Octree)
- [Linear octree](https://en.wikipedia.org/wiki/Linear_octree)
- [Z-order](https://en.wikipedia.org/wiki/Z-order_(curve))
- [UB-tree](https://en.wikipedia.org/wiki/UB-tree)
- [R-tree](https://en.wikipedia.org/wiki/R-tree)
- [R+ tree](https://en.wikipedia.org/wiki/R%2B_tree)
- [R* tree](https://en.wikipedia.org/wiki/R*_tree)
- [Hilbert R-tree](https://en.wikipedia.org/wiki/Hilbert_R-tree)
- [X-tree](https://en.wikipedia.org/wiki/X-tree)
- [Metric tree](https://en.wikipedia.org/wiki/Metric_tree)
- [Cover tree](https://en.wikipedia.org/wiki/Cover_tree)
- [M-tree](https://en.wikipedia.org/wiki/M-tree)
- [VP-tree](https://en.wikipedia.org/wiki/VP-tree)
- [BK-tree](https://en.wikipedia.org/wiki/BK-tree)
- [Bounding interval hierarchy](https://en.wikipedia.org/wiki/Bounding_interval_hierarchy)
- [Bounding volume hierarchy](https://en.wikipedia.org/wiki/Bounding_volume_hierarchy)
- [BSP tree](https://en.wikipedia.org/wiki/BSP_tree)
- [

Rapidly exploring random tree](https://en.wikipedia.org/wiki/Rapidly_exploring_random_tree)

#### Application-specific trees[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=15)]

- [Abstract syntax tree](https://en.wikipedia.org/wiki/Abstract_syntax_tree)
- [Parse tree](https://en.wikipedia.org/wiki/Parse_tree)
- [Decision tree](https://en.wikipedia.org/wiki/Decision_tree)
- [Alternating decision tree](https://en.wikipedia.org/wiki/Alternating_decision_tree)
- [Minimax tree](https://en.wikipedia.org/wiki/Minmax)
- [Expectiminimax tree](https://en.wikipedia.org/wiki/Expectiminimax_tree)
- [Finger tree](https://en.wikipedia.org/wiki/Finger_tree)
- [Expression tree](https://en.wikipedia.org/wiki/Expression_tree)
- [Log-structured merge-tree](https://en.wikipedia.org/wiki/Log-structured_merge-tree)
- [Lexicographic Search Tree](https://en.wikipedia.org/w/index.php?title=Lexicographic_Search_Tree&action=edit&redlink=1)

### Hash-based structures[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=16)]

- [Bloom filter](https://en.wikipedia.org/wiki/Bloom_filter)
- [Count-Min sketch](https://en.wikipedia.org/wiki/Count-Min_sketch)
- [Distributed hash table](https://en.wikipedia.org/wiki/Distributed_hash_table)
- [Double hashing](https://en.wikipedia.org/wiki/Double_hashing)
- [Dynamic perfect hash table](https://en.wikipedia.org/wiki/Dynamic_perfect_hashing)
- [Hash array mapped trie](https://en.wikipedia.org/wiki/Hash_array_mapped_trie)
- [Hash list](https://en.wikipedia.org/wiki/Hash_list)
- [Hash table](https://en.wikipedia.org/wiki/Hash_table)
- [Hash tree](https://en.wikipedia.org/wiki/Hash_tree_(disambiguation))
- [Hash trie](https://en.wikipedia.org/wiki/Hash_trie)
- [Koorde](https://en.wikipedia.org/wiki/Koorde)
- [Prefix hash tree](https://en.wikipedia.org/wiki/Prefix_hash_tree)
- [Rolling hash](https://en.wikipedia.org/wiki/Rolling_hash)
- [MinHash](https://en.wikipedia.org/wiki/MinHash)
- [Quotient filter](https://en.wikipedia.org/wiki/Quotient_filter)
- [Ctrie](https://en.wikipedia.org/wiki/Ctrie)

### Graphs[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=17)]

Many [graph](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics))-based data structures are used in computer science and related fields:

- [Graph](https://en.wikipedia.org/wiki/Graph_(data_structure))
- [Adjacency list](https://en.wikipedia.org/wiki/Adjacency_list)
- [Adjacency matrix](https://en.wikipedia.org/wiki/Adjacency_matrix)
- [Graph-structured stack](https://en.wikipedia.org/wiki/Graph-structured_stack)
- [Scene graph](https://en.wikipedia.org/wiki/Scene_graph)
- [Decision tree](https://en.wikipedia.org/wiki/Decision_tree)
    - [Binary decision diagram](https://en.wikipedia.org/wiki/Binary_decision_diagram)

- [Zero-suppressed decision diagram](https://en.wikipedia.org/wiki/Zero-suppressed_decision_diagram)
- [And-inverter graph](https://en.wikipedia.org/wiki/And-inverter_graph)
- [Directed graph](https://en.wikipedia.org/wiki/Directed_graph)
- [Directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph)
- [Propositional directed acyclic graph](https://en.wikipedia.org/wiki/Propositional_directed_acyclic_graph)
- [Multigraph](https://en.wikipedia.org/wiki/Multigraph)
- [Hypergraph](https://en.wikipedia.org/wiki/Hypergraph)

### Other[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=18)]

- [Lightmap](https://en.wikipedia.org/wiki/Lightmap)
- [

Winged edge](https://en.wikipedia.org/wiki/Winged_edge)
- [Quad-edge](https://en.wikipedia.org/wiki/Quad-edge)
- [Routing table](https://en.wikipedia.org/wiki/Routing_table)
- [Symbol table](https://en.wikipedia.org/wiki/Symbol_table)

### See also[[edit](https://en.wikipedia.org/w/index.php?title=List_of_data_structures&action=edit&section=19)]

[Purely functional data structure](https://en.wikipedia.org/wiki/Purely_functional_data_structure)

[hide]()

- [

v](https://en.wikipedia.org/wiki/Template:Data_structures)
- [

t](https://en.wikipedia.org/wiki/Template_talk:Data_structures)
- [

e](https://en.wikipedia.org/w/index.php?title=Template:Data_structures&action=edit)

[Data structures](https://en.wikipedia.org/wiki/Data_structure)

Types 

- [Collection](https://en.wikipedia.org/wiki/Collection_(abstract_data_type))
- [Container](https://en.wikipedia.org/wiki/Container_(abstract_data_type))

[Abstract](https://en.wikipedia.org/wiki/Abstract_data_type) 

- [Associative array](https://en.wikipedia.org/wiki/Associative_array) 
    - [Multimap](https://en.wikipedia.org/wiki/Multimap)

- [List](https://en.wikipedia.org/wiki/List_(abstract_data_type))
- [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))
- [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) 
    - [Double-ended queue](https://en.wikipedia.org/wiki/Double-ended_queue)

- [Priority 

queue](https://en.wikipedia.org/wiki/Priority_queue) 
    - [Double-ended priority queue](https://en.wikipedia.org/wiki/Double-ended_priority_queue)

- [Set](https://en.wikipedia.org/wiki/Set_(abstract_data_type)) 
    - [Multiset](https://en.wikipedia.org/wiki/Set_(abstract_data_type)#Multiset)
    - [Disjoint-set](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)

[Arrays](https://en.wikipedia.org/wiki/Array_data_structure) 

- [Bit array](https://en.wikipedia.org/wiki/Bit_array)
- [Circular buffer](https://en.wikipedia.org/wiki/Circular_buffer)
- [Dynamic array](https://en.wikipedia.org/wiki/Dynamic_array)
- [Hash table](https://en.wikipedia.org/wiki/Hash_table)
- [Hashed array tree](https://en.wikipedia.org/wiki/Hashed_array_tree)
- [Sparse matrix](https://en.wikipedia.org/wiki/Sparse_matrix)

[Linked](https://en.wikipedia.org/wiki/Linked_data_structure) 

- [Association list](https://en.wikipedia.org/wiki/Association_list)
- [Linked list](https://en.wikipedia.org/wiki/Linked_list)
- [Skip list](https://en.wikipedia.org/wiki/Skip_list)
- [Unrolled linked list](https://en.wikipedia.org/wiki/Unrolled_linked_list)
- [XOR linked list](https://en.wikipedia.org/wiki/XOR_linked_list)

[Trees](https://en.wikipedia.org/wiki/Tree_(data_structure)) 

- [B-tree](https://en.wikipedia.org/wiki/B-tree)
- [Binary search tree](https://en.wikipedia.org/wiki/Binary_search_tree) 
    - [AA tree](https://en.wikipedia.org/wiki/AA_tree)
    - [AVL tree](https://en.wikipedia.org/wiki/AVL_tree)
    - [Red–black tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
    - [Self-balancing tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)
    - [Splay tree](https://en.wikipedia.org/wiki/Splay_tree)

- [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure)) 
    - [Binary 

heap](https://en.wikipedia.org/wiki/Binary_heap)
    - [Binomial heap](https://en.wikipedia.org/wiki/Binomial_heap)
    - [Fibonacci heap](https://en.wikipedia.org/wiki/Fibonacci_heap)

- [R-tree](https://en.wikipedia.org/wiki/R-tree) 
    - [R* tree](https://en.wikipedia.org/wiki/R*_tree)
    - [R+ tree](https://en.wikipedia.org/wiki/R%2B_tree)
    - [Hilbert R-tree](https://en.wikipedia.org/wiki/Hilbert_R-tree)

- [Trie](https://en.wikipedia.org/wiki/Trie)
    - [Hash tree](https://en.wikipedia.org/wiki/Hash_tree_(persistent_data_structure))

[Graphs](https://en.wikipedia.org/wiki/Graph_(abstract_data_type)) 

- [Binary decision diagram](https://en.wikipedia.org/wiki/Binary_decision_diagram)
- [Directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph)
- [Directed acyclic word graph](https://en.wikipedia.org/wiki/Deterministic_acyclic_finite_state_automaton)
