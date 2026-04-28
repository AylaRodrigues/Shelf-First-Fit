# 🧩 Shelf First Fit Heuristic for the 2D Bin Packing Problem

This project aims to develop and implement a **Shelf First Fit construction heuristic** to solve the **2D Bin Packing Problem**, a widely studied challenge in the fields of optimization and logistics.

## 📦 Problem Description

Given a set of rectangular items, each with a known width and height, the challenge consists of packing them into a two-dimensional container of fixed dimensions **without overlapping**, aiming to **maximize the utilization of available space**.

The problem belongs to the **NP-hard** class, making constructive heuristics an efficient alternative for generating good solutions within a reduced computational timeframe.

## 📚 Shelf First Fit Heuristic

The **Shelf First Fit** heuristic organizes the packing as follows:

- The container is divided into horizontal **shelves** - Each item is placed in the **first available shelf** where it fits  
- If the item does not fit in any existing shelf, a **new shelf is created** - The height of the shelf is defined by the **tallest item allocated to it**
