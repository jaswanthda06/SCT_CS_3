# 🔐 Password Strength Checker Tool

##  Overview

This project is a **Password Strength Checker Tool** that evaluates the strength of a password based on several criteria:
- Length (minimum 8 characters)
- Presence of **uppercase letters**
- Presence of **lowercase letters**
- Presence of **digits**
- Presence of **special characters**

It provides both a **command-line interface (CLI)** and a **Graphical User Interface (GUI)** using Python’s Tkinter library.

---

##  Features

-  Real-time password evaluation
-  GUI with a clean, user-friendly interface
-  Clear strength feedback (Very Weak → Very Strong)
-  Modular and well-commented Python code
-  Easy to customize and expand

---

## 🔍 Password Strength Criteria

| Criteria                  | Points |
|---------------------------|--------|
| Length ≥ 8 characters     | +1     |
| Contains lowercase letter | +1     |
| Contains uppercase letter | +1     |
| Contains number           | +1     |
| Contains special symbol   | +1     |

**Total Score = 0 to 5**, mapped to strength levels like:

- 0-1: Very Weak 
- 2: Weak 
- 3: Moderate 
- 4: Strong 
- 5: Very Strong 

---

# 🛠️ Built With

Python 3.x

Tkinter (for GUI)

Regular Expressions (re module)

# 📄 License
This project is free to use for educational and non-commercial purposes.
