#  Mobile Scientific Calculator

The **Mobile Scientific Calculator** is a responsive web-based calculator built using **HTML, CSS, and JavaScript**. It provides both **basic arithmetic operations** and **scientific functions**, making it useful for students, engineers, and anyone who needs quick mathematical calculations on mobile or desktop devices.

The calculator features a modern **dark-themed interface**, touch-friendly buttons, and support for solving **simple mathematical equations**.

---

#  Project Overview

This project demonstrates how to build a fully functional **scientific calculator** using only frontend web technologies without any external libraries or frameworks.

The application supports:

- Basic arithmetic operations
- Scientific functions
- Real-time expression evaluation
- Simple equation solving

The interface is optimized for **mobile screens**, making it easy to use on smartphones.

---

#  Features

- ➕ Basic arithmetic operations (Addition, Subtraction, Multiplication, Division)
- 📐 Scientific functions
- 🧮 Square root calculation
- 📊 Logarithmic calculations
- 🔢 Decimal support
- 🧠 Equation solving feature
- 📱 Mobile-friendly responsive design
- 🎨 Modern dark UI
- ⚡ Fast real-time calculations
- 🧹 Clear button to reset the display
- ⚠️ Error handling for invalid expressions

---

# Supported Mathematical Functions

The calculator supports several scientific operations:

| Function | Description |
|--------|-------------|
| `sin(x)` | Sine function (degrees) |
| `cos(x)` | Cosine function (degrees) |
| `tan(x)` | Tangent function (degrees) |
| `log(x)` | Base-10 logarithm |
| `sqrt(x)` | Square root |
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |

Example expressions:
  sin(30)
  cos(60)
  log(100)
  sqrt(16)

---

# Equation Solver

The calculator includes a **basic equation solving feature**.

It can solve simple **linear equations containing one variable (x)**.

Example input:


2*x+4=10


Output:


x = 3


This feature calculates the value of **x** by evaluating both sides of the equation.

---

#  User Interface

The calculator interface includes:

### Display Screen
Shows the current expression or result.

### Number Buttons
Digits **0–9** and decimal point.

### Operator Buttons
Arithmetic operations like:

- Addition
- Subtraction
- Multiplication
- Division

### Scientific Buttons
Functions like:

- sin
- cos
- tan
- log
- sqrt

### Action Buttons

| Button | Function |
|------|---------|
| `=` | Calculate expression |
| `C` | Clear display |
| `Solve Equation` | Solve linear equation |

---

#  Technologies Used

| Technology | Purpose |
|-----------|--------|
| **HTML5** | Structure of the calculator |
| **CSS3** | Styling and layout |
| **JavaScript** | Calculator logic and functions |

---

The calculator will run instantly in your browser.

---

#  Mobile Optimization

The calculator layout is designed specifically for **mobile devices**.

Features include:

- Touch-friendly button sizes
- Responsive layout
- Compact screen design
- Smooth UI performance

---

# ⚙️ How the Calculator Works

The calculator works by:

1. Taking the expression entered by the user.
2. Replacing scientific functions with JavaScript `Math` operations.
3. Evaluating the expression using JavaScript.
4. Displaying the result on the screen.

Example transformation:


sin(30)


becomes


Math.sin(30 * π / 180)


This allows calculations using degrees.

---

#  Error Handling

The program includes basic error handling to prevent crashes.

If an invalid expression is entered, the display will show:


Error


This prevents the calculator from breaking due to incorrect inputs.

---

#  Possible Future Improvements

This calculator can be expanded with additional features such as:

- Scientific constants (π, e)
- Memory functions (M+, M-, MR)
- Advanced equation solver
- Graph plotting
- History of calculations
- Dark/light theme switch
- Keyboard input support
- Unit conversions
- Advanced math functions (power, factorial)

---

#  Learning Objectives

This project helps developers learn:

- Frontend web development
- JavaScript expression evaluation
- Responsive UI design
- Mathematical function implementation
- Mobile-first interface design

It is a great beginner project for those learning **JavaScript and web application development**.

---


#  Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork the project
- 🧑‍💻 Contribute improvements
- 📢 Share with others learning web development
