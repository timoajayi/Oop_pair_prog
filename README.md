# 🐍 Object-Oriented Programming (OOP) in Python

Welcome to the **OOP and Classes** learning repository! This hands-on repo will teach you the fundamentals of object-oriented programming in Python through interactive Jupyter notebooks.

## 📚 What You'll Learn

By completing this repo, you will:

- ✅ Understand the core principles of OOP: **Encapsulation**, **Inheritance**, and **Polymorphism**
- ✅ Create and use **classes** and **objects** in Python
- ✅ Define and work with **instance attributes**
- ✅ Write **methods** to add behavior to your classes
- ✅ Implement **composition** to build complex objects from simpler ones
- ✅ Use **inheritance** to create specialized classes from general ones
- ✅ Apply OOP concepts to real-world programming problems

## 🎯 Prerequisites

Before starting this repo, you should be comfortable with:

- Python basics (variables, data types, operators)
- Control flow (if/else, loops)
- Functions (defining and calling functions)
- Basic data structures (lists, dictionaries)

## 📖 repo Outline

Work through the notebooks **in order**, preferably as **pair programmers**:

| # | Topic | Notebook(s) | Description |
|---|-------|-------------|-------------|
| 1 | **Introduction to OOP** | [📓 Introduction](./pair_programming_practice/1_introduction_oop.ipynb) | Learn why OOP matters and understand core design principles |
| 2 | **Class Attributes** | [📓 Tutorial](./pair_programming_practice/2.1_class_attributes.ipynb) / [✏️ Exercise](./pair_programming_practice/2.2_class_attributes_exercise.ipynb) | Define classes with attributes using `__init__` and `self` |
| 3 | **Class Methods** | [📓 Tutorial](./pair_programming_practice/3.1_class_methods.ipynb) / [✏️ Exercise](./pair_programming_practice/3.2_class_methods_exercise.ipynb) | Add behavior to your classes with methods |
| 4 | **Composition & Inheritance** | [📓 Tutorial](./pair_programming_practice/4.1_composition_inheritance.ipynb) / [✏️ Exercise](./pair_programming_practice/4.2_composition_inheritance_exercise.ipynb) | Build complex class hierarchies and relationships |
| 5 | **Extra Practice** | [✏️ Assignments](./pair_programming_practice/5_extra_classes_assignments.ipynb) | Reinforce your learning with additional challenges |

> 💡 **Tip:** Each section includes both a tutorial notebook (📓) and hands-on exercises (✏️). Complete the tutorial first, then test your understanding with the exercises!

### 🎓 Live Session Notebooks

The live session will be led in class by a coach and focus on these notebooks:
- [📓 live_coding_oop_and_classes.ipynb](live_coding_oop_and_classes.ipynb)
- [📓 live_coding_inheritance.ipynb](live_coding_inheritance.ipynb)

## 🔗 Additional Resources

Looking for more? Check out our curated list of [extra learning resources](extra_learning_resources.md) including video tutorials and articles.

---

## Environment Setup

The [requirements.txt](requirements.txt) file contains all the necessary dependencies.

### macOS / Linux

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows

**PowerShell:**

```powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

**Git Bash:**

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```

> ⚠️ **Troubleshooting:** If you encounter errors during setup, try removing version numbers from the failing packages in `requirements.txt`.

---

## 🚀 Getting Started
1. Use this repo as Template
2. Make sure to include all branches and choose **yourself** as **Owner**
3. Git clone the repository on your computer in week2 folder
4. Set up your **environment** (see: [⚙️ Environment Setup](#environment-setup))
5. Launch **VS Code**
6. Open the [live coding oop and classes ](live_coding_oop_and_classes.ipynb) notebook.
7. Select the **kernel** associated with the Python virtual environment you created.
8. Start coding **together** with the coaches

