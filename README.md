# 📊 Multiplication Table Generator (Python)

This is a simple Python program that generates the multiplication table for any number entered by the user. The output is displayed in a clean format, showing the multiplication from 1 to 10.

---

## 📝 Description

This beginner-friendly project takes an integer input from the user and prints its multiplication table from 1 to 10 in the format `i * a = result`.

---

## 💻 Code

```python
a = int(input("Enter the multiplication table you desire: "))
for i in range(1, 11):
    print(i, "*", a, "=", i * a)

Enter the multiplication table you desire: 7
1 * 7 = 7
2 * 7 = 14
3 * 7 = 21
4 * 7 = 28
5 * 7 = 35
6 * 7 = 42
7 * 7 = 49
8 * 7 = 56
9 * 7 = 63
10 * 7 = 70
