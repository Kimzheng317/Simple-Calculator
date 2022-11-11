# Simple-Calculator
A stack based calculator that calculate the result by inputting math expression in string format and convert from infix expression to postfix expression
For example: A+B-C    ->      AB+C-

Calculation flow using Stack:
1. Push A into Stack
2. Push B into Stack
3. Do operation + and Push the result into Stack
4. Push C into Stack
5. Do operation - and Push the result into Stack
6. Pop the final result

Please take note that the string parameter will always consist of numbers and operators separated by spaces
Sample of test case:
Test Case 1: 1 + 1 * 3                   = 4
Test Case 2: 23 - ( 29.3 - 12.5 )        = 6.2
Test Case 3: 10 - ( 2 + 3 * ( 7 - 5 ) )  = 2
Test Case 4: 1 + ( 2 * 3 ) ^ 2           = 37

Development tools: https://www.programiz.com/csharp-programming/online-compiler/
