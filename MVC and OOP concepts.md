# Printable Handout: Lesson 2 – OOP & MVC Calculator with Copilot  
**Topic:** Coding a Calculator Using OOP and MVC Structure  
**For:** New Computer Science Students  
**Session:** 1 Hour  
**Languages:** Python, C#, or HTML/CSS/JavaScript

---

## Objective

- Learn the basics of Object-Oriented Programming (OOP)
- Understand the Model-View-Controller (MVC) design pattern
- Use GitHub Copilot to speed up OOP & MVC-based project development
- Build a simple calculator using these concepts

---

## 1. What is OOP?

**Object-Oriented Programming (OOP)** is a programming approach based on objects and classes.  
- **Class:** Blueprint for creating objects (e.g., Calculator)
- **Object:** Instance of a class
- **Key Concepts:**  
  - **Encapsulation:** Bundle data and methods
  - **Inheritance:** Create new classes from existing ones
  - **Polymorphism:** Use a unified interface for different data types
  - **Abstraction:** Hide complex details

---

## 2. What is MVC?

**Model-View-Controller (MVC)** is a design pattern to organize code:
- **Model:** Handles data and logic (e.g., Calculator operations)
- **View:** Handles user interface (e.g., Buttons, display)
- **Controller:** Handles user input and updates Model/View

---

## 3. Project Setup

**Choose a language:** Python, C#, or HTML/CSS/JavaScript  
(Ask your instructor which to use if unsure.)

**Folder Structure Example:**
```
calculator/
  model/
    calculator.py (or .cs, .js)
  view/
    view.py (or .cs, .js, .html/.css)
  controller/
    controller.py (or .cs, .js)
```

---

## 4. Using Copilot for OOP & MVC

### Example Prompts for Copilot

#### Python
- `# Create a Calculator class with add, subtract, multiply, and divide methods`
- `# Implement a Model class for calculator operations`
- `# Write a View class to display calculator output in the console`
- `# Implement a Controller class to handle user input and update the model and view`
- `# Connect the Model, View, and Controller classes in a main program`

#### C#
- `// Create a Calculator class with methods for basic arithmetic`
- `// Implement a Model class for calculator logic`
- `// Build a View class for displaying results`
- `// Write a Controller class to handle button clicks and input`
- `// Use MVC to wire everything together`

#### JavaScript (with HTML/CSS)
- `// Create a Calculator class with methods for operations`
- `// Implement a Model for calculator state`
- `// Create a View to update the calculator UI`
- `// Write a Controller to link button events with model updates`
- `// Integrate Model, View, and Controller in the main script`

---

## 5. Sample OOP & MVC Structure (Python Example)

### Model (model/calculator.py)
```python
class Calculator:
    def add(self, a, b):
        return a + b
    # Add subtract, multiply, divide methods
```

### View (view/view.py)
```python
class View:
    def show_result(self, result):
        print("Result:", result)
```

### Controller (controller/controller.py)
```python
class Controller:
    def __init__(self, model, view):
        self.model = model
        self.view = view
    def add_numbers(self, a, b):
        result = self.model.add(a, b)
        self.view.show_result(result)
```

---

## 6. Steps to Build with Copilot

1. **Create folders**: `model`, `view`, `controller`
2. **Create starter files**: e.g., `calculator.py`, `view.py`, `controller.py`
3. **Use Copilot prompts** from above to write code for each part
4. **Connect components** in a main script (e.g., `main.py`)
5. **Test:** Run and use your calculator

---

## 7. Checklist

- [ ] Chose a language
- [ ] Set up folders and files
- [ ] Used Copilot prompts for Model, View, Controller
- [ ] Connected MVC parts in main script
- [ ] Calculator works for basic operations

---

## 8. Resources

- [VS Code OOP Tutorial](https://code.visualstudio.com/docs/python/python-tutorial)
- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [MVC Pattern (Wikipedia)](https://en.wikipedia.org/wiki/Model–view–controller)

---

**End of Printable Handout**