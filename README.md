

# **AIM:**

To study and implement various programs using the `for` loop in Python including range usage, summation, matrix operations, prime number generation, and pattern printing.

---

# **THEORY :**

* **for loop:** Used to iterate over a sequence (range, list, matrix, etc.) and execute a block repeatedly.
* **range():** Generates a sequence of numbers in the format `range(start, stop, step)` (stop value excluded).
* **Nested loop:** A loop inside another loop, mainly used in matrix operations and patterns.
* **break statement:** Stops the loop when a condition is satisfied.
* **else with for:** Executes when loop completes normally without break.
* **Matrix traversal:** Uses nested loops to access rows and columns.
* **Pattern printing:** Uses loops and spacing logic to generate star patterns.

---

# ALGORITHMS 

---

## 1️ Print numbers from 1 to 5

1. Start the program.
2. Use `for i in range(1,6)`.
3. Print i in each iteration.
4. Stop when loop ends.

---

## 2️ Print odd numbers between 1 to 10

1. Start the program.
2. Use `range(1,11,2)` to increment by 2.
3. Print each value of i.
4. Stop.

---

## 3️ Sum of first n numbers

1. Start the program.
2. Take n as integer input.
3. Initialize sum = 0.
4. Run loop from 1 to n using `range(1,n+1)`.
5. Add each number to sum.
6. Print total sum.
7. Stop.

---

## 4️ Display 3×3 Matrix (Nested Loop Method)

1. Start the program.
2. Define 3×3 matrix A.
3. Use outer loop for rows (range(3)).
4. Use inner loop for columns (range(3)).
5. Print each element A[i][j].
6. After each row, print newline.
7. Stop.

---

## 5️ Display Matrix (Row Method)

1. Start the program.
2. Define matrix A.
3. Use `for row in A`.
4. Print each row directly.
5. Stop.

---

## 6️ Multiplication of two 3×3 matrices

1. Start the program.
2. Define matrices A and B.
3. Initialize result matrix with zeros.
4. Use three nested loops:

   * Outer loop for rows of A.
   * Middle loop for columns of B.
   * Inner loop for multiplication and summation.
5. Store result in result[i][j].
6. Print the result matrix.
7. Stop.

---

## 7️ Print prime numbers in range 2 to 50

1. Start the program.
2. Use loop from 2 to 49.
3. For each number, check divisibility from 2 to i-1.
4. If divisible, break loop.
5. If loop completes without break, print number (prime).
6. Stop.

---

## 8️ Right Angle Triangle Pattern

1. Start the program.
2. Loop from 1 to 5.
3. Print `"* "` multiplied by i.
4. Stop.

---

## 9️ Pyramid Pattern (Increasing)

1. Start the program.
2. Loop rows from 0 to 5.
3. Print spaces using `" "*(6-rows)`.
4. Print stars using `"* "*rows`.
5. Stop.

---

## 10 Inverted Pyramid Pattern

1. Start the program.
2. Loop rows from 5 down to 1 using negative step.
3. Print spaces accordingly.
4. Print decreasing number of stars.
5. Stop.

---

# **CONCLUSION :**

In this experiment, various applications of the for loop were studied including number generation, summation, matrix operations, prime number checking, and pattern printing. Nested loops were used for matrix multiplication and pattern formation. The range function helped control loop execution efficiently. Overall, the for loop is powerful for structured and controlled iteration in Python.

---


