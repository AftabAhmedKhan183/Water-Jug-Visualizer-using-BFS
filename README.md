💧 Water Jug Problem Visualizer (BFS)

An interactive visualization of the **Water Jug Problem** using the **Breadth-First Search (BFS)** algorithm. This project demonstrates how Artificial Intelligence search techniques can be applied to solve classical state-space problems while providing a real-time graphical visualization of each step.

---

## 📖 About the Project

The **Water Jug Problem** is a well-known Artificial Intelligence problem in which two jugs with fixed capacities are used to measure a specific target amount of water.

This project uses the **Breadth-First Search (BFS)** algorithm to find the shortest sequence of operations required to reach the target quantity.

The visualization displays:

- 💧 Water level inside each jug
- 🔄 Step-by-step BFS traversal
- 📝 Log of every state visited
- ⚡ Smooth animations for better understanding

---

## 🚀 Features

- Interactive graphical visualization
- Adjustable jug capacities
- Custom target water quantity
- Breadth-First Search implementation
- Shortest solution path
- Animated water level changes
- Step-by-step execution log
- Clean and responsive UI
- Reset functionality


## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Breadth-First Search (BFS)
- State Space Search


## 🧠 Algorithm Used

### Breadth-First Search (BFS)

BFS explores every possible state level by level until the target state is found.

Each state is represented as:

```
(Jug A Water, Jug B Water)
```

Possible operations:

- Fill Jug A
- Fill Jug B
- Empty Jug A
- Empty Jug B
- Pour A → B
- Pour B → A

Since BFS explores states level-wise, it guarantees the **minimum number of operations** needed to reach the target state.

---

## 📂 Project Structure

```
Water-Jug-Visualizer/
│
├── index.html          # Complete project (HTML + CSS + JavaScript)
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/AftabAhmedKhan183/Water-Jug-Visualizer.git
```

2. Open the project folder.

3. Open **index.html** in any modern web browser.

No additional installation or dependencies are required.

---

## 💻 Input

The user can enter:

- Capacity of Jug A
- Capacity of Jug B
- Target amount of water

Example:

| Jug A | Jug B | Target |
|-------|-------|--------|
| 4 | 3 | 2 |

---

## 📈 Example Output

```
Step 0 : (0,0)

Step 1 : (4,0)

Step 2 : (1,3)

Step 3 : (1,0)

Step 4 : (0,1)

Step 5 : (4,1)

Step 6 : (2,3)
```

Target achieved:
```
Jug A = 2 Litres
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Artificial Intelligence search techniques
- State Space Representation
- Breadth-First Search (BFS)
- Graph Traversal
- Queue Data Structure
- Problem Solving using AI
- Frontend Visualization using JavaScript

---

## 📚 AI Concepts Covered

- State Space Search
- Breadth-First Search (BFS)
- Graph Traversal
- Queue
- Visited State Tracking
- Shortest Path Search

---

## 👨‍💻 Author

**Aftab Ahmed Khan**

Computer Science Engineering Student at NITP

---

## ⭐ If you like this project

Give this repository a **Star ⭐** on GitHub!
