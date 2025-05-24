# 🐍 Python Interview Questions

A comprehensive guide covering Python interview questions from beginner to advanced. Whether preparing for your first job or switching roles, this repo will help you revise essential Python concepts.

---

## 📚 Topics Covered

- [Python Basics](./basics.md)
- [Data Structures](./data-structures.md)
- [Object-Oriented Programming (OOP)](./oops.md)
- [Advanced Concepts](./advanced.md)
- [Standard Libraries & Modules](./modules.md)
- [Coding Questions](./coding-questions.md)
- [Resources](./resources.md)

---

## 🚀 Contribution

Feel free to add questions, correct errors, or suggest improvements.

---

<details>

 <summary>🐍 Python Basics</summary>

### 1. 🔍 **What are Python’s built-in data types?**

🐍 Python provides several built-in 🧱 data types to handle different kinds of 📦 data:

#### 🔢 **Numeric Types**

* `int` ➡️ Whole numbers (e.g., `5`, `-20`)
* `float` ➡️ Decimal numbers (e.g., `3.14`, `-0.001`)
* `complex` ➡️ Complex numbers (e.g., `3 + 4j`)

#### 🔡 **Sequence Types**

* `str` ➡️ Text (e.g., "hello")
* `list` ➡️ Mutable 🧺 (e.g., `[1, 2, 3]`)
* `tuple` ➡️ Immutable 🪙 (e.g., `(1, 2, 3)`)
* `range` ➡️ Sequence used for loops (e.g., `range(5)`)

#### 🧩 **Set Types**

* `set` ➡️ Unique unordered 📚 (e.g., `{1, 2, 3}`)
* `frozenset` ➡️ Immutable version of `set`

#### 🗺️ **Mapping Type**

* `dict` ➡️ Key-value 🔑 (e.g., `{"name": "Alice"}`)

#### ⚖️ **Boolean Type**

* `bool` ➡️ `True` / `False`

#### 🧬 **Binary Types**

* `bytes`, `bytearray`, `memoryview` ➡️ Used for byte-level operations

#### 🚫 **None Type**

* `NoneType` ➡️ Represents no value (`None`)

---

### 2. 📊 **Why is Python used extensively in Data Science?**

Python 🐍 is widely used in Data Science for the following reasons:

* 📚 **Rich Library Ecosystem**: Powerful libraries like `pandas`, `numpy`, `matplotlib`, `scikit-learn` simplify data manipulation and analysis
* 🤖 **Machine Learning & AI Tools**: Integration with frameworks like `TensorFlow`, `PyTorch`, and `Keras`
* 📈 **Data Visualization Capabilities**: Tools like `matplotlib`, `seaborn`, and `plotly` help create insightful charts
* 🌐 **Large Supportive Community**: Extensive documentation and active contributors
* 🧪 **Easy to Learn and Use**: Simple, readable syntax enables fast prototyping

---

### 3. 📦 **Explain the difference between lists and tuples in Python.**

* 🔄 `list`: Mutable, meaning it can be modified after creation
* 🪙 `tuple`: Immutable, meaning it cannot be changed once defined
* ✅ Use `list` when the data may change, and `tuple` when the data should remain constant

---

### 4. 🧠 **What are Python’s predefined keywords and their uses?**

* Python contains reserved keywords like `if`, `else`, `elif`, `for`, `while`, `def`, `return`, `import`, etc.
* These keywords have special meaning in Python and cannot be used as identifiers (variable or function names)

---

### 5. 🔄 **How does Python handle mutability and immutability?**

* 📦 Mutable objects (e.g., `list`, `dict`, `set`) can be modified in place
* 🪙 Immutable objects (e.g., `int`, `str`, `tuple`) cannot be modified after creation

---

### 6. 🧩 **What is the significance of mutability in Python data structures?**

* 🔧 Mutability allows objects to be changed without creating new ones, which is memory-efficient
* 🧱 Immutability ensures stability, predictability, and safety in multi-threaded environments

---

### 7. 🧮 **Explain different types of operators in Python (Arithmetic, Logical, etc.)**

* ➕ **Arithmetic Operators**: `+`, `-`, `*`, `/`, `//`, `%`, `**`
* 🧠 **Logical Operators**: `and`, `or`, `not`
* 📊 **Comparison Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
* 🧲 **Bitwise Operators**: `&`, `|`, `^`, `~`, `<<`, `>>`
* 🧱 **Assignment Operators**: `=`, `+=`, `-=`, `*=`, `/=`, etc.

---

### 8. 🔁 **How do you perform type casting in Python?**

* Type casting is done using functions like `int()`, `float()`, `str()`, `bool()`, etc.
* Example: `int("42")` converts the string to an integer

---

### 9. 🔍 **Explain the difference between implicit and explicit type casting in Python**

* 🧠 **Implicit Type Casting**: Python automatically converts one data type to another when needed

  * Example: `int + float` → Python converts the `int` to `float`
* ✋ **Explicit Type Casting**: Programmer manually changes the data type

  * Example: `float("3.14")`

---

### 10. ⚙️ **What is the significance of conditionals in Python?**

* 🧭 Conditionals (`if`, `elif`, `else`) are used to execute different blocks of code depending on conditions
* Enables decision-making in programs

---

### 11. 🔁 **How would you implement a switch-case statement in Python?**

* Python does not have a native `switch-case` construct
* Can be implemented using `if-elif-else` statements or dictionary-based function mapping

---

### 12. 🔂 **What are loops in Python? How do you differentiate between for and while loops?**

* 🔁 `for` loop: Iterates over a sequence (e.g., list, tuple, range)
* 🔁 `while` loop: Runs as long as a condition is `True`

---

### 13. 🔄 **How do you use break, continue, and pass in Python loops?**

* 🚪 `break`: Exits the loop prematurely
* ⏭️ `continue`: Skips the current iteration and moves to the next
* 🪶 `pass`: Does nothing, used as a placeholder

</details>

## 📫 Contact

- [LinkedIn – Sugata Mondal](https://linkedin.com/in/sugatamondal)
- [GitHub – CoderSugata](https://github.com/CoderSugata)
