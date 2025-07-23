# Binary Search Tree Visualization (Java Swing & Java FX)

## 🌳 Project Overview

This project is a **graphical visualization of a Binary Search Tree (BST)** implemented using **Java Swing**. 
It allows users to dynamically **add** or **delete nodes** and visually observe how the tree structure updates accordingly.
The GUI also displays real-time **Inorder, Preorder, Postorder traversals**, and the **height of the tree**.

This project is especially helpful for:
- Students learning data structures.
- Visual learners wanting a hands-on understanding of tree structures.
- Educators demonstrating how BSTs behave dynamically.

---

## 🖼️ Features

- ✅ Dynamic insertion and deletion of nodes in the BST.
- ✅ Visual connection between parent and child nodes.
- ✅ Real-time updates of:
  - Inorder Traversal
  - Preorder Traversal
  - Postorder Traversal
  - Height of the tree
- ✅ Smart node positioning to avoid overlapping.
- ✅ Keyboard shortcuts for faster interaction (`A/a/Enter` to add, `D/d` to delete).
- ✅ User-friendly GUI with Swing components.

---

## 📷 GUI Layout

- **Top Panel**:
  - **Left**: Displays BST Height.
  - **Right**: TextField for data input, and Add/Delete buttons.
  
- **Center Panel**: Tree visual representation using JLabels connected by lines.

- **Bottom Panel**: Displays Inorder, Preorder, and Postorder traversal results.

---

## 🎮 Controls & Usage

### ✅ Add Node
- Type an integer in the input field.
- Press `Add` button **OR**
- Press **A**, **a**, or **Enter** key.

### ❌ Delete Node
- Type the integer value of the node to delete.
- Press `Delete` button **OR**
- Press **D** or **d** key.

---

## 🛠️ How It Works

- **Each node** is a `JLabel` showing the data and positioned according to BST rules.
- **Lines** are drawn using `Graphics2D` to represent parent-child connections.
- **Traversal logic** (inorder, preorder, postorder) is implemented recursively.
- **Height** is calculated dynamically after each insertion/deletion.
- Node placement adapts based on subtree depth and balance.

---

## 🚀 Getting Started

### ✅ Prerequisites
- Java Development Kit (JDK 8 or higher)
- Any IDE (e.g., IntelliJ IDEA, Eclipse)
- Basic understanding of Java Swing and Binary Trees

### 🧪 Running the Application

1. Clone or download the repository.
2. Open the project in your IDE.
3. Run `BSTVisualization.java`.
4. The GUI window will launch automatically.

### 🧾 Sample Preloaded Tree (in `main()`):
bst.add(500);
bst.add(250);
bst.add(350);
bst.add(200);
bst.add(750);
bst.add(1000);
bst.add(700);
bst.add(740);
