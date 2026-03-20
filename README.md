# 🧠 Python Quiz App (OOP Based)

A simple command-line quiz application built using **Python Object-Oriented Programming**.  
This project demonstrates how to use classes, objects, lists, and user input to create a quiz system.

The app loads questions from a data file, converts them into objects, and controls the quiz flow using a QuizBrain class.

---

## 🚀 Features

- ✅ Object-Oriented Design
- ✅ Question class for question objects
- ✅ QuizBrain class to control quiz flow
- ✅ Questions stored in external data file
- ✅ User input for answers
- ✅ Dynamic question list
- ✅ Clean and modular code

---

## 📂 Project Structure
  quiz-project/
  │
  ├── main.py
  ├── data.py
  ├── question_model.py
  ├── quiz_brain.py
  └── README.md

  
### File Description

| File | Purpose |
|------|---------|
| main.py | Starts the quiz and creates objects |
| data.py | Stores question data |
| question_model.py | Question class |
| quiz_brain.py | Controls quiz logic |

---

## 🧩 How It Works

1. Questions are stored in `data.py`
2. Each question is converted into a `Question` object
3. All objects are stored in a list
4. QuizBrain reads the list
5. QuizBrain shows questions one by one
6. User enters True / False
7. Quiz continues until questions end

---

## 🛠 Example Code

```python
quiz = QuizBrain(question_bank)
quiz.next_question()
