### Java Operators, Control Flow, and Methods**  

## **Exercise 1: Advanced Arithmetic and Logical Operations**
#### **Objective:**  
Practice using **arithmetic, assignment, and logical operators** in real-world calculations.

#### **Tasks:**  
1. Create a **Java class** called `MathOperations`.  
2. Declare and initialize three variables:  
   - `salary = 50000` (monthly salary)  
   - `taxRate = 0.2` (20% tax)  
   - `bonus = 5000` (monthly bonus)  
3. Calculate and print:  
   - The **net salary after tax** (use `salary - (salary * taxRate)`)  
   - The **total earnings** after adding the `bonus`  
4. Use **comparison operators** (`>`, `<`, `==`) to check:
   - If the net salary is greater than `40000`
   - If the total earnings are equal to `55000`
5. Use **logical operators** (`&&`, `||`) to:
   - Check if the net salary is greater than `40000` **AND** the total earnings exceed `50000`.
   - Check if the net salary is less than `30000` **OR** the bonus is greater than `4000`.

#### **Expected Output Example:**
```
Net Salary after tax: 40000.0
Total earnings after bonus: 45000.0
Net salary > 40000: false
Total earnings == 55000: false
Condition (Net Salary > 40000 && Total Earnings > 50000): false
Condition (Net Salary < 30000 || Bonus > 4000): true
```

---

## **Exercise 2: Control Flow - Conditional Statements & Loops**
#### **Objective:**  
Improve decision-making skills using **if-else, switch-case, and loops**.

#### **Tasks:**  
1. Create a Java class `ControlFlowDemo`.  
2. Implement a method `evaluateGrade(int score)` that:
   - Takes a **score (0-100)**
   - Uses an **if-else statement** to print:
     - `"Excellent"` if the score is **90 or above**
     - `"Good"` if between **70 and 89**
     - `"Average"` if between **50 and 69**
     - `"Fail"` otherwise  
3. Create a **switch-case** structure for selecting a **day of the week** based on an integer (1-7).  
4. Write a **for-loop** that prints numbers **from 1 to 10** but skips **multiples of 3**.

#### **Expected Output Example:**
```
Score: 85, Grade: Good
Day 4 is: Thursday
1
2
4
5
7
8
10
```

---

## **Exercise 3: Methods and Functionality**
#### **Objective:**  
Practice **creating and using methods** with parameters and return types.

#### **Tasks:**  
1. Create a **Java class** called `BankAccount`.  
2. Define:
   - A `balance` variable.
   - A constructor that initializes the balance.
   - A `deposit(int amount)` method to increase the balance.
   - A `withdraw(int amount)` method that:
     - Allows withdrawal **only if** the balance is sufficient.
     - Prints `"Insufficient funds"` if not.
   - A `displayBalance()` method to print the balance.  
3. In `main()`, create an object of `BankAccount`, deposit money, withdraw, and display the balance.

#### **Expected Output Example:**
```
Initial Balance: 1000
Depositing 500...
New Balance: 1500
Withdrawing 2000...
Insufficient funds
Withdrawing 300...
New Balance: 1200
```

---

## **References:**
### **1. Operators in Java:**  
- [Java Operators - Oracle Documentation](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)  
- [GeeksForGeeks - Java Operators](https://www.geeksforgeeks.org/operators-in-java/)  

### **2. Control Flow in Java:**  
- [Java If-Else, Switch-Case - Oracle Docs](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/if.html)  
- [Loops in Java - W3Schools](https://www.w3schools.com/java/java_while_loop.asp)  

### **3. Java Methods & OOP:**  
- [Methods in Java - Oracle Docs](https://docs.oracle.com/javase/tutorial/java/javaOO/methods.html)  
- [Java Classes and Objects - JavaTPoint](https://www.javatpoint.com/java-oops-concepts)  

---

### **Challenge Question (Optional)**
- Modify **Exercise 3** to allow **multiple users** (each having a separate balance).  
- Implement a `transfer(int amount, BankAccount recipient)` method to **send money** between accounts.

---

### 🔥 **Bonus Fun Fact:**  
If you were coding this in **PHP**, you'd probably have `undefined variable` errors all over the place! 😆 But Java keeps things structured and safe.  

