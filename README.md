# Day20-50-days-coding-challenge
## 🔹 Problem 1: Evaluate Reverse Polish Notation

### 🧮 Problem Statement:
Given a list of strings `tokens` that represent an arithmetic expression in Reverse Polish Notation (RPN), evaluate the expression.

### ✅ RPN Rules:
- Valid operators: `+`, `-`, `*`, `/`
- Operands are integers (can be negative).
- Division truncates toward zero.
- The input is always valid (no division by zero).

### 💡 Approach:
- Use a stack to process the tokens.
- If the token is a number, push to stack.
- If the token is an operator, pop two elements from the stack, apply the operator, and push the result.

### ✅ Examples:
```plaintext
## 🔹 Problem 1: Evaluate Reverse Polish Notation

### 🧮 Problem Statement:
Given a list of strings `tokens` that represent an arithmetic expression in Reverse Polish Notation (RPN), evaluate the expression.

### ✅ RPN Rules:
- Valid operators: `+`, `-`, `*`, `/`
- Operands are integers (can be negative).
- Division truncates toward zero.
- The input is always valid (no division by zero).

### 💡 Approach:
- Use a stack to process the tokens.
- If the token is a number, push to stack.
- If the token is an operator, pop two elements from the stack, apply the operator, and push the result.

### ✅ Examples:
```plaintext
Input: ["2", "1", "+", "3", "*"]  
Output: 9

Input: ["4", "13", "5", "/", "+"]  
Output: 6

Input: ["10","6","9","3","+","-11","*","/","*","17","+","5","+"]  
Output: 22



🔹 Problem 2: Greatest Common Divisor of Min and Max
🧮 Problem Statement:
Given an integer array nums, return the greatest common divisor (GCD) of the smallest and largest elements.

✅ Constraints:
2 ≤ nums.length ≤ 1000

1 ≤ nums[i] ≤ 1000

💡 Approach:
Find the minimum and maximum elements in the array.

Use math.gcd() to find the GCD between them.

✅ Examples:
Input: [2, 5, 6, 9, 10] → Output: 2  
Input: [7, 5, 6, 8, 3] → Output: 1  
Input: [3, 3] → Output: 3


#
