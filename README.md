# 🔐 PyPassword Generator

A simple Python program that generates a **random, secure password** based on user preferences.
The user chooses how many **letters, numbers, and symbols** the password should contain, and the program generates a randomized password accordingly.

---

## 📌 How It Works

1. The program asks the user:
   - How many letters to include
   - How many symbols to include
   - How many numbers to include
2. Random characters are selected from predefined lists.
3. All selected characters are:
   - Stored in a list
   - Shuffled to ensure randomness
4. The final password is displayed to the user.

---

## 🧠 Features

- Uses both uppercase and lowercase letters
- Includes numbers and special symbols
- Fully randomized character order
- User-controlled password complexity

---

## 🛠️ Technologies Used

- Python 3
- random module

---

## ▶️ How to Run the Program

1. Make sure **Python 3** is installed.
2. Save the script as `main.py`.
3. Run the program from the terminal:

```bash
python main.py
```

4. Follow the on-screen instructions to generate your password.

---

## 🧪 Example Output

```
Welcome to the PyPassword Generator!
How many letters would you like in your password?
5
How many symbols would you like?
2
How many numbers would you like?
3

Your password is: aB3!9d$2Q
```

---

## 🎯 Purpose of the Project

This project was created to:
- Practice working with lists in Python
- Use loops and user input
- Learn how to generate randomness
- Understand basic password security concepts

---

## 🚀 Possible Improvements

- Add minimum and maximum limits
- Copy password to clipboard
- Add password strength indicator
- Allow user to exclude certain characters
