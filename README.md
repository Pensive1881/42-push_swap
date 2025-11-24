# push_swap

This repository contains my solution to the **push_swap** project from 42.  
The goal is to sort a list of integers using only a limited set of operations on two stacks.

## 🔧 Allowed operations

- `sa` / `sb` / `ss`
- `pa` / `pb`
- `ra` / `rb` / `rr`
- `rra` / `rrb` / `rrr`

## 📌 Project description

The program receives a list of integers and prints the sequence of operations needed to sort them in ascending order.  
The objective is to use **as few operations as possible**, while handling:

- Duplicates (error)
- Non-numeric input (error)
- Integer overflow (error)

## 🧠 Approach

- Simple sorting logic for very small sets  
- Optimized algorithm for larger inputs to reduce operation count  
  *(update this section if needed to match your implementation)*

## 🏗️ Compilation

```bash
make

