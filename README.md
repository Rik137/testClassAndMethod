# Arithmetic Operations in Java ➕

This is a simple Java program that demonstrates basic arithmetic operations using a custom `Arithmetic` class.  
It supports addition, multiplication, and finding the larger or smaller of two numbers.

---

## 📌 Features
- **Addition** of two numbers.
- **Multiplication** of two numbers.
- Find the **larger number**.
- Find the **smaller number**.

---

## 🛠️ Requirements
- **Java 8+** installed on your system.

---

## ▶️ How to Use

```java
// Create an Arithmetic object with two numbers
Arithmetic values = new Arithmetic(9, 7);

// Perform operations
System.out.println(values.addition());       // Output: 16
System.out.println(values.multiplication()); // Output: 63
System.out.println(values.moreNumber());     // Output: 9
System.out.println(values.lessNumber());     // Output: 7
🎮 Example Output
16
63
9
7
