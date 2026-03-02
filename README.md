# git-lab
a lab to learn the good practices of git

## ⚠️ The Golden Rule

NEVER commit directly to the main branch.
Always create a new branch for your changes.

## 🚀 How to Run the App

We have included a graphical interface (main.py) to test your code.

1. Open VS Code.
2. Open the terminal (Ctrl + ).
3. Run the app:

```
python main.py
```


4. Try clicking the buttons. If a function (like "Multiply") hasn't been written yet, the app will tell you!

## 📋 Your Assignment

Your goal is to add a mathematical function to calculator.py without breaking your teammates' code.

**Step-by-Step Instructions**

1. **Clone the Repo**

    - Open VS Code.

    - Press F1 -> Git: Clone.

    - Paste the URL of this repo.

2. **Create Your Branch**

    - Click main in the bottom-left corner.

    - Select + Create new branch.

    -  Name it: feature/yourname-operation (e.g., feature/alex-multiply).

3. **Write Code**

    - Open calculator.py.

    - Add your assigned function (subtract, multiply, divide, modulo).

    - Do not delete the existing add function!

4. **Save & Push**

    - Go to the Source Control tab (the "Y" icon).

    -  Stage your changes (+).

    - Commit with a message: "Add multiplication function".

    - Click Publish Branch (Cloud icon).

5. **Pull Request**

    - Go to this repo on GitHub.

    - Click Compare & pull request on the yellow banner.

    - Create the PR and assign your Team Lead to review it.

## 🆘 Troubleshooting

- **Merge Conflict?** Don't panic. Click "Accept Incoming" or "Accept Current" in VS Code to decide which code stays.

- **Detached Head?** You are lost in time. Create a new branch immediately to save your spot.





OUR PROJECT :


## Project Purpose

This lab was designed to practice good Git workflow and collaborative development.

The objectives of this project are:

- Learn how to use Git branches properly

- Avoid committing directly to the main branch

- Implement calculator functions in a separate module

- Test the implementation using a graphical interface

## Application Overview

This project is a simple calculator application built in Python.

It consists of:

- A graphical interface using Tkinter (main.py)

- A calculation logic module (calculator.py)

- A fallback CLI mode if Tkinter is not available

The GUI dynamically calls functions from the calculator module using getattr().
If a function is missing, the application displays a warning message instead of crashing.

## Features

Addition

Subtraction

Multiplication

Division

Modulo

Error handling for invalid numeric input

Warning message if a function is not implemented

Automatic switch to CLI mode if GUI is unavailable

## Project Structure

calculator_lab/
│── main.py
│── calculator.py
│── README.md

- main.py → Interface and application control

- calculator.py → Mathematical operations

- README.md → Project documentation

  ## Git Workflow

We follow this rule:

Never commit directly to the main branch.

Workflow:

Create a new branch

Implement your feature

Commit your changes

Push the branch

Open a Pull Request

Merge after validation

git checkout -b feature-add
git add .
git commit -m "Add addition function"
git push origin feature-add

## How to run 

python main.py

If Tkinter is not installed, the application will automatically run in CLI mode.


