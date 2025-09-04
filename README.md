```markdown
# Trie Data Structure in Python

This repository contains an implementation of a **Trie (prefix tree)** in Python, built from scratch using a Jupyter Notebook.

## 📌 Features
- Insert words into the trie
- Check if a word exists (`contains`)
- Find all words with a given prefix (`contains_prefix`)
- Delete words from the trie
- Implemented in an easy-to-read, object-oriented style

## 📂 Project Structure
```

├── Trie.ipynb   # Jupyter Notebook with implementation and tests
└── README.md    # Documentation

````

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook

Install Jupyter if you don’t already have it:
```bash
pip install notebook
````

### Running the Notebook

Start Jupyter:

```bash
jupyter notebook
```

Open **`Trie.ipynb`** in the browser and run the cells to experiment.

## 🧑‍💻 Example Usage

```python
from trie import Trie

trie = Trie()
trie.add("can")
trie.add("cane")

print(trie.contains("can"))      # True
print(trie.contains("car"))      # False
print(trie.contains_prefix("ca")) # ['can', 'cane']

trie.delete("can")
print(trie.contains("can"))      # False
```

## 📚 Applications of Trie

* Autocomplete systems
* Spell checkers
* IP routing
* Dictionary implementations

```

