### Python---Data-Structures-and-Conditionals
### Data Structures - List, Dictionary, Set & Conditional Statements

This repository consist of a Python assignment demonstrating fundamental operations on Lists, Dictionaries, and Sets, alongside conditional evaluation logic (if-elif-else) to classify performance scores and handle edge cases.

## 📝 Overview
This repository contains solutions to foundational Python exercises. The project covers:
* Constructing and manipulating **Lists** using built-in methods.
* Indexing, slicing, and computing statistical properties (`max`, `min`, `sum`).
* Managing key-value pairs using **Dictionaries**.
* Exploring **Set** properties (uniqueness, immutability of elements, set algebra).
* Applying **Conditional Statements** (`if`, `elif`, `else`) to build an interactive performance-scoring program.

---

## 📚 Topics Covered

| Data Structure / Concept | Core Operations / Methods |
| :--- | :--- |
| **List** | `append()`, `insert()`, `remove()`, `pop()`, `extend()`, `sort()`, indexing, slicing |
| **Dictionary** | Key-value mapping, value updates, `.keys()`, `.values()`, `.items()` |
| **Set** | Uniqueness, duplicate filtering, `.union()`, `.intersection()` |
| **Conditionals** | `if`, `elif`, `else`, logical operators (`and`), range checks |

---

## 🛠️ Assignment Breakdown

### 1. Lists
* **Creation & Modification:** Built `age_list` and `name_list`. Practiced appending, inserting at specific indices, removing by value, popping elements, extending, and sorting in descending order.
* **Aggregations:** Evaluated `max()`, `min()`, and `sum()` on numeric list elements.
* **Accessing Elements:** Used zero-based indexing (`list[0]`), negative indexing (`list[-1]`), slicing (`list[2:5]`), and step-reversal (`list[::-1]`).

### 2. Dictionaries
* Created `student_marks` mapping student names to numeric scores (0–100 scale).
* Accessed and updated specific student scores.
* Displayed dictionary structures using `.keys()`, `.values()`, and `.items()`.

### 3. Sets
* **Duplicate Elimination:** Analyzed how sets automatically filter redundant values from initialization lists.
* **Error Analysis:** Confirmed that sets do not support item assignment (`TypeError`) due to being unordered collections.
* **Set Operations:** Computed the **union** and **intersection** of two numeric sets (`set1` and `set2`).

### 4. Conditional Statements
Built an interactive **Performance Category Program**:
* Accepts user input scores between `0` and `10`.
* Evaluates scores using range logic:
  * **Above Average:** Score $> 7$
  * **Average:** Score between $4$ and $7$ (inclusive)
  * **Below Average:** Score $< 4$
* Provides tailored encouragement and feedback for each category.

## 🚀 How to Run

### Running in Jupyter Notebook / JupyterLab
1. Clone or download this repository.
2. Open Jupyter Notebook / JupyterLab in your working directory.
3. Open the `.ipynb` file and execute cells sequentially (`Shift + Enter`).
