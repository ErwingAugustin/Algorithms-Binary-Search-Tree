# Algorithms-Binary-Search-Tree
High-performance C++ implementation of a Binary Search Tree for processing large-scale auction data
# Auction Data Analysis | Binary Search Tree (C++)

## Project Overview
This project implements a **Binary Search Tree (BST)** in C++ to manage and search through large datasets of auction bids. It demonstrates advanced knowledge of data structures, pointer management, and algorithmic efficiency.

## Technical Highlights
* **Efficient Searching:** Utilizes a BST to achieve **O(log n)** search time, allowing the system to handle thousands of records with minimal latency.
* **Memory Management:** Implemented custom logic for node insertion, deletion, and tree traversal (In-Order) while maintaining memory safety in C++.
* **Data Parsing:** Integrated a custom CSV parser to ingest and process real-world monthly sales data.

## Performance Comparison
| Data Structure | Search Complexity | Use Case |
| :--- | :--- | :--- |
| Linked List | O(n) | Small, unsorted datasets |
| **Binary Search Tree** | **O(log n)** | **Large-scale, searchable datasets** |

## How to Run
1. Compile the project: `g++ BinarySearchTree.cpp CSVparser.cpp -o AuctionBST`
2. Run the executable: `./AuctionBST`
