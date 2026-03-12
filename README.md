# 🌳 AVL Tree Visualizer

A web-based **Data Structures visualization project** that demonstrates
how **AVL Trees maintain balance using rotations**.

Users can insert, delete, search, and traverse nodes while visually
observing balancing operations.

🔗 **Live Demo:** (Add your Netlify link here)

------------------------------------------------------------------------

# 📚 About the Project

An **AVL Tree** is a self-balancing Binary Search Tree where the
**balance factor** of each node is maintained between **-1 and +1**.

Balance Factor = Height(left subtree) − Height(right subtree)

If the tree becomes unbalanced, **rotations** are applied to restore
balance.

------------------------------------------------------------------------

# ⚡ BST Operation Complexity

  Operation   Average    Worst
  ----------- ---------- -------
  Search      O(log n)   O(n)
  Insert      O(log n)   O(n)
  Delete      O(log n)   O(n)

Balanced trees like AVL ensure operations remain close to **O(log n)**.

------------------------------------------------------------------------

# 🔄 AVL Tree Rotations

**LL Rotation** -- Right rotation when insertion occurs in left subtree
of left child.

**RR Rotation** -- Left rotation when insertion occurs in right subtree
of right child.

**LR Rotation** -- Left rotation followed by Right rotation.

**RL Rotation** -- Right rotation followed by Left rotation.

------------------------------------------------------------------------

# ⚔️ AVL vs Red‑Black Trees

  Feature         AVL Tree         Red‑Black Tree
  --------------- ---------------- -----------------
  Balance         Strict           Relaxed
  Search speed    Faster           Slightly slower
  Insert/Delete   More rotations   Fewer rotations

**AVL:** Best for search-heavy systems\
**Red‑Black:** Best for frequent updates

------------------------------------------------------------------------

# 🚀 Features

-   Insert nodes
-   Delete nodes
-   Search nodes
-   Preorder / Inorder / Postorder traversal
-   AVL rotation visualization
-   Step-by-step insertion
-   Random tree generation
-   Dark / Light theme

------------------------------------------------------------------------

# 🛠 Tech Stack

-   HTML
-   CSS
-   JavaScript
-   SVG

------------------------------------------------------------------------

# 📂 Project Structure

AVL-TREE-VISUALISER │ ├── index.html └── README.md

------------------------------------------------------------------------

# 🌐 Deployment

This project is deployed using **Netlify**.

Steps: 1. Push project to GitHub 2. Connect repository to Netlify 3.
Deploy

------------------------------------------------------------------------

# 🎯 Example

Example insertion:

Insert: 10, 20, 30

After balancing:

      20
     /  \

10 30

------------------------------------------------------------------------

# 👨‍💻 Author

**Harikrishna**\
B.Tech -- Computer Science\
DSA Visualization Project
