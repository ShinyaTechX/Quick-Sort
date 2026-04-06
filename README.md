# Quick Sort Algorithm

**Efficient sorting algorithm implemented in Python** – a clean and educational implementation of Quick Sort.

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Visual Tree](#VisualTree)
---

## About
Quick Sort is a widely used sorting algorithm based on the **divide-and-conquer** approach.  
This project provides a Python implementation that is simple, readable, and educational, making it easy to learn or integrate into other projects.

---

## Features
- Pure Python implementation
- Sorts lists of numbers or strings
- Handles empty lists and duplicate values
- Easy-to-read code for educational purposes
- Can be extended for custom comparison functions

---

## VisualTree
                [8,3,1,7,0,10,2]
                       |
                      (2)
          -------------------------
         |                         |
     [1,0]                   [8,3,7,10]
       |                         |
      (0)                       (10)
   ---------               -------------
  []       [1]        [8,3,7]        []
                         |
                        (7)
                   ---------
                  [3]     [8]

## Installation
Clone the repository and navigate into it:

```bash
git clone https://github.com/ShinyaTechX/Quick-Sort.git
cd Quick-Sort
