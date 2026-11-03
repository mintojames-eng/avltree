Self-Balancing Binary Search Tree
Overview
Implementation and comparison of a Plain Binary Search Tree (BST)
and AVL Tree for the MediQueue patient ID system.
Objectives
- Implement BST insertion, search, deletion and traversal.
- Implement AVL self-balancing with rotations.
- Compare height, search cost and performance.
- Study Red-Black Tree as a self-learning extension.
Technologies
- Python
- Google Colab
- No built-in balanced-tree libraries
Implemented Trees
Plain BST
Supports: - Insert - Search - Delete - In-order traversal - Height
calculation - BST validation
AVL Tree
Supports: - Insert and delete with rebalancing - Balance factor - LL,
RR, LR and RL rotations - Height and balance validation
Workloads
The trees are tested with: - Sequential IDs - Random IDs - Nearly sorted
IDs (about 5% swaps)

Dataset sizes: 1000, 5000 and 10000

Performance measurements include: - Final height - Insertion time - AVL
rotation count - Average successful search comparisons - Height after
deleting 20% of nodes
Sample Demonstration
Input: [10, 20, 30, 40, 50, 25]

Expected: - BST root = 10, height = 5 - AVL root = 30, height =
3 - AVL rotations = 4 - Both produce the same sorted in-order
traversal
How to Run
In Google Colab:
    file name:Minto_532_lab6
Or locally:
python Minto_532_lab6.py

_
