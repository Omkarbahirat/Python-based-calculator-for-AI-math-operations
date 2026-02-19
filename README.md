# Python-based-calculator-for-AI-math-operations
# AI Maths Calculator (NumPy) — Google Colab Project

## Overview

This project is a Python-based interactive **AI Mathematics Calculator** implemented in **Google Colab** using the **NumPy** library.
The notebook allows users to perform important mathematical operations commonly used in Machine Learning and Neural Networks, such as matrix operations and activation functions.

Instead of hard-coded values, the user enters matrices, vectors, or numbers at runtime, and the program computes the result dynamically.

---

## Features

The calculator supports the following operations:

1. **Matrix Multiplication**
2. **Vector Dot Product**
3. **Sigmoid Activation Function**
4. **ReLU (Rectified Linear Unit)**
5. **Softmax Function**

These functions are fundamental in Artificial Intelligence and Deep Learning, especially in neural network computations.

---

## Technologies Used

* Python
* Google Colab (Jupyter Notebook)
* NumPy Library

---

## How the Program Works

The notebook runs a menu-driven calculator:

After running all cells, the user is prompted to choose an operation:

```
1. Matrix multiplication
2. Vector dot product
3. Sigmoid function
4. ReLU function
5. Softmax function
6. Exit
```

The program then asks for user input (matrix/vector/value), processes it using NumPy, and displays the computed result.

---

## How to Run the Project

### Method 1 — Run on Google Colab

1. Open the `.ipynb` file in Google Colab
2. Click **Runtime → Run All**
3. Follow the menu instructions in the output cell
4. Enter values in Python format:

   * Matrix example: `[[1,2],[3,4]]`
   * Vector example: `[1,2,3]`
   * Single value: `5`

---

## Requirements

Install the required library (already available in Colab):

```
numpy
```

If running locally:

```bash
pip install numpy
```

---

## Concepts Demonstrated

This project demonstrates core concepts used in Artificial Intelligence:

* Linear Algebra (Matrices & Vectors)
* Neural Network Activation Functions
* Numerical Computation using NumPy
* Interactive Python Programs

---

## Important Note

Inputs are taken using Python evaluation format.
Therefore values must be entered exactly in Python list form:

Correct:

```
[1,2,3]
[[1,2],[3,4]]
```

Incorrect:

```
1,2,3
1 2 3
```

---

## Future Improvements

* Add graphical visualization of activation functions
* Add more operations (transpose, determinant, inverse)
* Replace manual input with a GUI interface
* Convert into a full web ap
