# Palindrome Number Program in C

## 📌 Description
This program checks whether a given number is a **palindrome** or not using the **C programming language**.

A palindrome number is a number that remains the same when its digits are reversed.  
Example: `121`, `1331`, `404`

---

## 🧠 Logic Used
1. Store the **original number**
2. Reverse the number using:
   - `while` loop
   - digit extraction (`% 10`)
3. Compare the **original number** with the **reversed number**
4. If both are equal → Palindrome

---

## 🧾 Algorithm
1. Read an integer `num`
2. Store it in `original`
3. Initialize `reverse = 0`
4. While `num > 0`:
   - Extract digit using `digit = num % 10`
   - Reverse number using `reverse = reverse * 10 + digit`
   - Remove last digit using `num = num / 10`
5. Compare `original` and `reverse`
6. Display result

## Author

SOUMYANK CHANDRASEN
