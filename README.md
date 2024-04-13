# Splay-Tree

C program that implements Splay Tree, a self-adjusting binary search tree with the property that recently accessed elements are quick to access again. The program allows for the insertion of nodes into the tree, splaying a specified node to the root, and deleting a node from the tree. Additionally, it incorporates explanations of the Zig, Zag, and Zig-Zag operations, fundamental to Splay Tree restructuring.


**Key Features**

  - Node Insertion: Nodes can be inserted into the Splay Tree using the insert operation.
    
  - Splaying: The splay operation brings a specified node to the root of the tree, adjusting the tree structure based on the node's position.

  - Node Deletion: Nodes can be deleted from the Splay Tree, and the tree structure is adjusted accordingly.


**Zig, Zag, and Zig-Zag Operations**

  - Zig Rotation: A rotation performed when a node is the left child of its parent and its parent is the left child of its parent. It brings the node closer to the root by making it the new root's parent.
    
  - Zag Rotation: A rotation performed when a node is the right child of its parent and its parent is the right child of its parent. It brings the node closer to the root by making it the new root's parent.
    
  - Zig-Zag Rotation: A combination of Zig and Zag rotations, used to bring a node closer to the root when it has a different orientation than its parent and grandparent.


# Note
Splay Trees are widely used in applications requiring efficient access to recently accessed elements, such as caching mechanisms in web browsers and database systems. This program serves as an educational tool for understanding the basic operations of Splay Trees and their restructuring techniques.
