# 🌳 AVL Tree Visualizer -- DSA Project

## 📌 Project Overview

This project demonstrates the working of a **Self-Balancing Binary
Search Tree (AVL Tree)** through an interactive web-based visualization.

The application allows users to insert, delete, search, and traverse
nodes while visually observing how AVL Trees maintain balance through
rotations.

The project is implemented using **HTML, CSS, and JavaScript** and
deployed as a web application.

------------------------------------------------------------------------

# 1️⃣ Binary Search Tree (BST) Operations and Time Complexity

A **Binary Search Tree (BST)** is a hierarchical data structure where: -
Left subtree contains values **less than** the root - Right subtree
contains values **greater than** the root

### Common Operations

  Operation   Average Time   Worst Case
  ----------- -------------- ------------
  Search      O(log n)       O(n)
  Insert      O(log n)       O(n)
  Delete      O(log n)       O(n)

### Problem with BST

If the tree becomes **skewed**, operations degrade to **O(n)**.

Example:

1\
2\
3\
4

------------------------------------------------------------------------

# 2️⃣ Why Do We Need a Balanced BST?

Balanced trees maintain **minimum height**, ensuring efficient
operations.

Benefits: - Faster searching - Efficient insertion - Efficient
deletion - Guarantees **O(log n)** operations

------------------------------------------------------------------------

# 3️⃣ Introduction to AVL Trees

An **AVL Tree** is a self-balancing Binary Search Tree invented by: -
Adelson‑Velsky - Landis

### Balance Factor

BF = height(left subtree) − height(right subtree)

Allowed values: -1, 0, +1

If BF goes outside this range, rotations are performed to rebalance the
tree.

------------------------------------------------------------------------

# 4️⃣ Types of AVL Tree Imbalance

### 1️⃣ Left‑Left (LL)

Occurs when insertion happens in the **left subtree of the left child**.

Solution: **Right Rotation**

### 2️⃣ Right‑Right (RR)

Occurs when insertion happens in the **right subtree of the right
child**.

Solution: **Left Rotation**

### 3️⃣ Left‑Right (LR)

Occurs when insertion happens in the **right subtree of the left
child**.

Solution: **Left Rotation → Right Rotation**

### 4️⃣ Right‑Left (RL)

Occurs when insertion happens in the **left subtree of the right
child**.

Solution: **Right Rotation → Left Rotation**

------------------------------------------------------------------------

# 5️⃣ AVL Trees vs Red‑Black Trees

  Feature        AVL Tree               Red‑Black Tree
  -------------- ---------------------- ------------------------
  Balance        Strict                 Less strict
  Search speed   Faster                 Slightly slower
  Rotations      More rotations         Fewer rotations
  Usage          Lookup‑heavy systems   Frequent insert/delete

### When to Use

**AVL Tree** - Databases - Lookup-heavy applications - Searching
intensive tasks

**Red‑Black Tree** - Operating systems - Standard libraries (C++ STL,
Java TreeMap) - Frequent modifications

------------------------------------------------------------------------

# 6️⃣ Project Features

-   Insert nodes
-   Delete nodes
-   Search nodes
-   Preorder traversal
-   Inorder traversal
-   Postorder traversal
-   BFS traversal
-   Step‑by‑step AVL insertion
-   AVL rotations visualization
-   Tree height and node count display
-   Undo functionality
-   Random tree generation
-   Dark / Light theme

------------------------------------------------------------------------

# 7️⃣ Technologies Used

-   HTML5
-   CSS3
-   JavaScript
-   SVG for tree visualization

------------------------------------------------------------------------

# 8️⃣ Project Structure

AVL-TREE-VISUALISER │ ├── index.html └── README.md

------------------------------------------------------------------------

# 9️⃣ Deployment

Deploy on: - Netlify - Vercel - Render

Add your deployed link here.

------------------------------------------------------------------------

# 🔟 How to Run the Project

Clone the repository:

git clone https://github.com/KHarikrishna2006/AVL-TREE-VISUALISER.git

Open the folder:

cd AVL-TREE-VISUALISER

Open **index.html** in your browser.

------------------------------------------------------------------------

# 🎯 Learning Outcomes

Through this project we learn:

-   Binary Search Tree operations
-   Self-balancing trees
-   AVL rotations
-   Visualization of data structures
-   Web-based algorithm simulation
