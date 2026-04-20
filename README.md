# DFA Simulator — Theory of Computation

An interactive **Deterministic Finite Automata (DFA) Simulator** built using **HTML, CSS, and Vanilla JavaScript**.
This project visually demonstrates how DFA processes input strings step-by-step with real-time transitions and graphical representation.

---

## 🚀 Features

* Multiple predefined DFA machines:

  * Ends with `1`
  * Divisible by 3 (binary)
  * Starts with `"ab"`
  * Even number of `0s` and `1s`
  * No consecutive `"aa"`

* Interactive state diagram (Canvas-based)

* Step-by-step execution

* Auto-run with speed control

* Input string tester

* Tape-style visualization

* Batch testing for multiple inputs

* Accept / Reject result display

* Clean and responsive UI

---

## 🛠 Technologies Used

* HTML5
* CSS3 (Flexbox + Grid + Custom Styling)
* JavaScript (Vanilla JS)
* Canvas API (for DFA visualization)

---

## 📂 Project Structure

project-folder/
│
└── index.html   (contains HTML, CSS, and JS)

> This is a single-file project (everything is inside index.html)

---

## ▶️ How to Run

1. Download or clone the project:

   git clone https://github.com/munideep18/DFA.git

2. Open the folder

3. Run the project by opening:

   index.html

4. It will open in your browser 🎉

---

## 🧠 How It Works

* Each DFA is defined using:

  * States (Q)
  * Alphabet (Σ)
  * Transition function (δ)
  * Start state
  * Accept states

* Simulation process:

  1. User enters input string
  2. Machine reads one symbol at a time
  3. Transitions between states
  4. Ends when input is finished
  5. Final state determines:

     * ACCEPT ✅
     * REJECT ❌

---

## 🧪 Sample Use Cases

* Check if a binary string ends with 1
* Verify if a number is divisible by 3
* Validate strings starting with "ab"
* Check parity of 0s and 1s
* Detect invalid patterns like "aa"

---

## 🎓 Learning Purpose

This project helps students understand:

* DFA concepts visually
* State transitions clearly
* Language acceptance conditions
* Automata theory fundamentals

---

## 🔮 Future Improvements

* Add custom DFA builder
* Support for NFA
* NFA to DFA conversion
* Save/load machines
* Better mobile responsiveness

---

## 🤝 Contributing

You can improve this project by:

* Adding new DFA examples
* Improving UI/UX
* Optimizing animations

Pull requests are welcome.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Munideep

---
