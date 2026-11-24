# 🧠 ARRAY NEXUS — Memory Laboratory

### Interactive Array Data Structures Simulator

**ARRAY NEXUS** is a futuristic, interactive web-based simulator designed to demonstrate fundamental **Array Data Structure concepts in C++** through visual animations and step-by-step explanations.

The project was created as an academic assignment for **Data Structures in C++**


---

## 🚀 Project Overview

ARRAY NEXUS transforms traditional array operations into an interactive **Memory Laboratory**.

Instead of only displaying code, the simulator visually demonstrates how array elements are stored in memory and how different operations affect them.

### Main Modules

* 🧠 **Memory Lab**
* 📍 **Address Engine**
* ⚡ **Insertion Reactor**
* 🗑️ **Deletion Protocol**
* 🔎 **Search Scanner**
* 🎯 **Mission Mode**

---

## ✨ Features

### 1. 🧠 Memory Lab

Displays the array as a visual memory grid.

Each element shows:

* Array index
* Element value
* Simulated memory address
* Base address
* Element width

The simulator uses:

```text
Base Address = 1000
Element Width = 4 bytes
```

---

### 2. 📍 Address Engine

The Address Engine demonstrates the standard array address calculation formula:

```text
LOC(A[i]) = Base + (i − LB) × W
```

Where:

* `Base` = Base address of the array
* `i` = Index of the required element
* `LB` = Lower bound of the array
* `W` = Size of each element in bytes

### Example

For:

```text
Base = 1000
LB = 0
W = 4
i = 3
```

The address is:

```text
LOC(A[3]) = 1000 + (3 − 0) × 4
          = 1012
```

---

### 3. ⚡ Insertion Reactor

Demonstrates insertion of a new element into an array.

The simulator visually shows the elements being shifted toward the right before placing the new element.

### Complexity

```text
Worst Case: O(n)
```

---

### 4. 🗑️ Deletion Protocol

Demonstrates deletion of an element from an array.

After removing the selected element, the remaining elements are shifted toward the left.

### Complexity

```text
Worst Case: O(n)
```

---

### 5. 🔎 Search Scanner

The Search Scanner contains two searching techniques.

#### Linear Search

Checks array elements one by one until the required element is found.

```text
Time Complexity: O(n)
```

#### Binary Search

Searches for an element by repeatedly dividing a **sorted array** into smaller sections.

```text
Time Complexity: O(log n)
```

The simulator displays the changing search range during the process.

---

## 🎯 Mission Mode

Mission Mode adds a gamified learning experience.

Users answer Data Structures questions and receive **XP points** for correct answers.

This feature was added to make the simulator more interactive and different from a traditional array visualizer.

---

## 🎨 Design Concept

The project uses a futuristic **Memory Laboratory** theme.

The design includes:

* Dark cyber-style interface
* Glowing memory cells
* Interactive panels
* Operation console
* Visual search animations
* Complexity indicators
* Learning challenges

The goal is to make Data Structures concepts easier to understand visually.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **C++17** for reference implementation

No external libraries or frameworks are required.

---

## 📂 Project Structure

```text
ARRAY-NEXUS/
│
├── index.html
├── README.md
├── array_simulation.cpp
├── PROMPTS_AND_RESULTS.txt
└── screenshots/
    ├── 01_main_memory_lab.png
    ├── 02_address_engine.png
    ├── 03_insertion_reactor.png
    ├── 04_deletion_protocol.png
    ├── 05_search_scanner.png
    └── 06_mission_mode.png
```

---

## ▶️ How to Run

### Method 1 — Directly in Browser

1. Download or clone this repository.
2. Open `index.html`.
3. The simulator will run directly in your browser.

No installation is required.

---

### Method 2 — GitHub Pages

The project can be hosted using GitHub Pages.

1. Create a GitHub repository.
2. Upload `index.html`.
3. Go to **Settings → Pages**.
4. Select:

   * Branch: `main`
   * Folder: `/ (root)`
5. Click **Save**.
6. GitHub will generate a public website link.

Example:

```text
https://YOUR-USERNAME.github.io/array-nexus/
```

---

## 🧪 Operations Demonstrated

| Operation           | Demonstration              | Complexity |
| ------------------- | -------------------------- | ---------- |
| Address Calculation | Memory address calculation | O(1)       |
| Insertion           | Right shifting             | O(n)       |
| Deletion            | Left shifting              | O(n)       |
| Linear Search       | Sequential checking        | O(n)       |
| Binary Search       | Divide-and-search          | O(log n)   |

---

## 💡 Learning Outcomes

After using this simulator, students can understand:

* How arrays are stored in memory
* How array addresses are calculated
* How insertion works internally
* How deletion works internally
* How linear search operates
* Why binary search requires sorted data
* Difference between O(1), O(n), and O(log n)
* How array operations affect memory positions

---

## 🧩 Academic Requirements Covered

This project covers the major requirements of the assignment:

* ✅ Interactive webpage
* ✅ Array address calculation
* ✅ Array insertion
* ✅ Array deletion
* ✅ Linear search
* ✅ Binary search
* ✅ Visual simulation
* ✅ Prompt engineering
* ✅ Creative UI
* ✅ Interactive learning features
* ✅ Error/edge-case handling
* ✅ Documentation and screenshots

---

## 🤖 Prompt Engineering

The project was developed using iterative prompts to improve:

1. Initial simulator generation
2. C++ concept alignment
3. Input validation and edge cases
4. UI creativity
5. Testing and correctness

The complete prompt history and results are included in:

```text
PROMPTS_AND_RESULTS.txt
```

---

## 📜 License

This project is created for **educational and academic purposes**.

---

## 👨‍💻 Author

**Kashish Pathak**

CSE [Cyber Security]
Acropolis Institute of Technology and Research

> **ARRAY NEXUS — Turning Arrays into a Memory Experience.**
