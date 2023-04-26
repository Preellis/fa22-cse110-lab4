1. The bug was that the sum was calculated using strings so the numbers were concatenated as strings instead of added.
2. We can fix this by casting num1 and num2 to Number inside the result calculation.
![fix](fix.png)