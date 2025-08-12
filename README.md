
# Custom Dataset and DataLoader in PyTorch

This repository demonstrates how to create a **custom dataset** class in PyTorch by subclassing the `torch.utils.data.Dataset` class.  
It provides a minimal, clear example of how to store, access, and prepare data for training using the `DataLoader`.

---

## 📜 Overview

The code defines a `CustomDataset` class that:
- Stores features and labels.
- Implements `__len__()` to return dataset size.
- Implements `__getitem__()` to retrieve a single data point (feature, label pair) by index.

---
🧠 How It Works
Initialization (__init__)

Stores features and labels in object variables.

Length (__len__)

Returns total number of samples.

Get Item (__getitem__)

Retrieves the (feature, label) pair for a given index.

---
📦 Requirements
Python 3.8+

PyTorch

---
📄 License
This project is licensed under the MIT License.

---
✍️ Author
Created by Saniya Chhabra.

