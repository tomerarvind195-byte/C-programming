# 🚀 C++ Data Structures & Algorithms (DSA)

> A comprehensive collection of **Data Structures and Algorithms (DSA)** programs implemented in **C++**, covering fundamental concepts, problem-solving techniques, and coding interview questions.

![C++](https://img.shields.io/badge/C%2B%2B-17-blue?style=flat\&logo=c%2B%2B)
![DSA](https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms-orange?style=flat)
![Platform](https://img.shields.io/badge/Platform-CLI-black?style=flat\&logo=windowsterminal)
![Practice](https://img.shields.io/badge/Coding-Interview%20Preparation-green?style=flat)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)

---

# 📸 Demo

> *[(Add screenshots of your program output here)]*

```text
===========================================
      C++ Data Structures & Algorithms
===========================================

1. Arrays
2. Linked List
3. Stack
4. Queue
5. Tree
6. Graph
7. Sorting Algorithms
8. Searching Algorithms

Choose an option: 7

Sorting Algorithms
------------------------
1. Bubble Sort
2. Selection Sort
3. Insertion Sort
4. Merge Sort
5. Quick Sort

Enter your choice:
```

---

# 📋 About The Project

This repository contains **C++ implementations of Data Structures and Algorithms** designed to strengthen programming skills, improve logical thinking, and prepare for coding interviews and competitive programming.

Each program is written with **clean code, proper comments, and beginner-friendly logic**, making it easy to understand and practice.

### Key Highlights

* Covers fundamental Data Structures
* Includes popular Sorting & Searching Algorithms
* Beginner-friendly implementations
* Optimized solutions wherever applicable
* Well-structured folder organization
* Easy to compile and run

---

# ✨ Features

* ✅ Arrays
* ✅ Strings
* ✅ Linked List
* ✅ Stack
* ✅ Queue
* ✅ Trees
* ✅ Binary Search Tree (BST)
* ✅ Graph
* ✅ Hashing Basics
* ✅ Recursion
* ✅ Sorting Algorithms
* ✅ Searching Algorithms
* ✅ Time Complexity Analysis
* ✅ Coding Interview Problems
* ✅ Competitive Programming Practice

---

# 🛠️ Tech Stack

| Component       | Technology           |
| --------------- | -------------------- |
| Language        | C++                  |
| Standard        | C++                |
| IDE             | VS Code / CodeBlocks |
| Compiler        | GCC / G++            |
| Version Control | Git & GitHub         |

---

# 🚀 Getting Started

## Prerequisites

* C++ Compiler (GCC / G++)
* VS Code / CodeBlocks
* Git

------

## Installation

```bash
# Clone repository
git clone https://github.com/tomerarvind195-byte/cpp-dsa.git

# Go inside project
cd cpp-dsa

# Compile program
g++ filename.cpp -o program

# Run
./program
```

For Windows:

```bash
g++ filename.cpp -o program.exe
program.exe
```

---

# 📚 Topics Covered

## Data Structures

* Arrays
* Strings
* Linked List
* Stack
* Queue
* Deque
* Priority Queue
* Trees
* Binary Search Tree
* Heap
* Graph
* Hash Table

---

## Algorithms

### Sorting

* Bubble Sort
* Selection Sort
* Insertion Sort
* Merge Sort
* Quick Sort
* Heap Sort

### Searching

* Linear Search
* Binary Search

### Recursion

* Factorial
* Fibonacci
* Backtracking Basics

### Graph Algorithms

* BFS
* DFS

---

# 📂 Project Structure

```text
cpp-dsa/
│
├── Arrays/
├── Strings/
├── LinkedList/
├── Stack/
├── Queue/
├── Trees/
├── Graph/
├── Sorting/
├── Searching/
├── Recursion/
├── Practice Questions/
├── README.md
└── LICENSE
```

---

# 💡 Example Program

```cpp
#include<iostream>
using namespace std;

int binarySearch(int arr[], int n, int key)
{
    int low = 0;
    int high = n - 1;

    while(low <= high)
    {
        int mid = (low + high) / 2;

        if(arr[mid] == key)
            return mid;

        if(arr[mid] < key)
            low = mid + 1;
        else
            high = mid - 1;
    }

    return -1;
}

int main()
{
    int arr[] = {10,20,30,40,50};
    int n = 5;

    cout << binarySearch(arr,n,30);

    return 0;
}
```

---

# 🎯 Learning Outcomes

After completing this repository, you will understand:

* Problem-solving techniques
* Time & Space Complexity
* Object-Oriented Programming basics
* Efficient algorithms
* Coding interview preparation
* Competitive programming fundamentals

---

# 🔮 Future Improvements

* [ ] Dynamic Programming
* [ ] Greedy Algorithms
* [ ] Trie
* [ ] Segment Tree
* [ ] Disjoint Set Union (DSU)
* [ ] Advanced Graph Algorithms
* [ ] LeetCode Solutions
* [ ] Codeforces Practice
* [ ] STL Examples

---

# 🤝 Contributing

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-algorithm
```

3. Commit your changes

```bash
git commit -m "Added Dijkstra Algorithm"
```

4. Push to GitHub

```bash
git push origin feature/new-algorithm
```

5. Create a Pull Request

---

# 👨‍💻 Author

**Arvind Kumar**

🎓 3rd Year B.Tech (Information Technology)

💻 Aspiring Software Engineer | C++ & DSA Enthusiast

🌐 LinkedIn: https://www.linkedin.com/in/arvind-kumar-399a60338

💻 GitHub: https://github.com/tomerarvind195-byte

📧 Email: [tomerarvind195@gmail.com](mailto:tomerarvind195@gmail.com) 
📧. Email: [arvind.it.24023@recb.ac.in]
---

# 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you found this repository helpful, don't forget to **Star** it on GitHub!
