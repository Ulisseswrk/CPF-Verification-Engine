# 🧠 CPF-Verification-Engine

**CPF-Verification-Engine** is a simple and functional Python program that checks whether a Brazilian CPF number is valid or not, based on the official verification digit algorithm.

This was a personal challenge created before completing my Python courses, with the goal of practicing input handling, data validation, control structures, and logic implementation in a real-world scenario.

---

## 🚀 Features

- ✅ Accepts CPF input with or without formatting (dots and hyphen)  
- ⚠️ Detects non-numeric input and prompts the user again  
- 🔢 Calculates and verifies the two CPF check digits  
- 🧹 Cleans and processes the input into a numeric list  
- 📌 Provides user feedback: "CPF verídico ✅" or "CPF inválido ❌"

---

## 🧩 Technologies

- Python 3  
- Basic concepts of:  
  - Input handling  
  - Error handling (try, except, finally)  
  - Lists and loops  
  - Mathematical operations for CPF digit verification

---

## 💡 How It Works

1. The user is prompted to enter a CPF number.  
2. The program removes formatting characters like . and -.  
3. It verifies the length and ensures all characters are digits.  
4. Calculates the first and second verification digits using the official CPF formula.  
5. Compares the result with the original input.  
6. Outputs whether the CPF is valid or not.

---

## 📌 Example
Digite seu CPF: 123.456.789-09
CPF inválido ❌

Digite seu CPF: 39053344705
CPF verídico ✅

---

## 🧪 Possible Improvements

- Add unit tests for CPF validation logic  
- Convert script to a function or class for reuse  
- Create a simple GUI using Tkinter or a web version with Flask

---

## 📚 Learning Outcome

This project helped solidify my understanding of:

- Data validation and sanitization  
- Control flow with loops and conditionals  
- The importance of breaking problems into logical steps

---

## 🛠️ How to Run

Make sure Python 3 is installed, then run:

bash
python cpf_verification.py

---

## 👨‍💻 Author
Developed by Ulisses, a Software Engineering student at FIAP, passionate about technology, problem-solving, and continuous learning.
