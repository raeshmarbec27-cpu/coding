# Adjacent Stick Game - C++ Solution

This repository contains a C++ solution for the "Adjacent Stick Game" coding challenge.

## 📝 Problem Statement
Mukesh and his friends are on vacation in Coorg. During a campfire activity called the **"Adjacent Stick Game"**, sticks of different lengths are placed in a line. 

**The Rules:**
1. Mukesh must remove one stick from every **adjacent pair** of sticks.
2. The remaining sticks are combined to form one larger stick.
3. The goal is to calculate the **smallest possible length** of the resulting combined stick.

### Constraints
- N (Number of sticks) ≤ 50.
- N is always even.

## 💻 Sample Test Cases

**Input 1:**
4
2 1 3 1
**Output 1:**
2
**Input 2:**
5
1 3 1 2 4
**Output 2:**
6

## 🛠️ Implementation Details
- **Language:** C++
- **Logic:** The program reads the number of sticks and their lengths into a vector, then iterates through the pairs to calculate the minimum total length by selecting the optimal sticks from each adjacent pair.

