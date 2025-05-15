# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the sum of all elements in a list.

## 🧠 Algorithm
1.Define a list of numbers.

2.Use Python’s built-in sum() function to calculate the total.

3.Print the result.

## 🧾 Program
```python
 L=[153,147,124,102] 
print(sum(L)))
```
## Output
![444006247-7c7feb30-030c-4bd8-879e-288be391d9a7](https://github.com/user-attachments/assets/2dc43272-f847-4276-b7df-809f4c481428)

## Result
Thus, the program has been executed successfully.


---

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## 🧠 Algorithm
1.Import the re module.

2.Initialize an empty list l1 to store results.

3.Define a list of words:
- items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

4.Iterate through each word in the list:
- Use re.search(r"e", i) to check if the word contains 'e'.
- If not, append the word to l1.
  
5.Print the final filtered list.
  
## 🧾 Program
```python
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = [item for item in items if not re.search(r'e', item)]
print(result)
```
## Output
![444007087-e6a41898-12e3-43bb-bc88-0f89667f43a5](https://github.com/user-attachments/assets/cfff0f94-c854-4688-94d7-33c061292653)

## Result
Thus,the program has been executed successfully.

---

# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1.Define a function named remove that takes the input string as an argument.

2.Read the index n from the user input.

3.Initialize an empty string a to store the new string.

4.Iterate over each index of the string using a for loop.

5.Check if the current index i is not equal to n.

6.If i != n, append the character at index i to string a.

7.After the loop, return the modified string a.

8.Print the final result.

## 💻 Program
```python
def remove(a):
    n=int(input())
    s=a[:n]+a[n+1:]
    print(s)
```
## Output
![444007944-29489962-e5bb-42a9-9244-cfbf0488111e](https://github.com/user-attachments/assets/507c0900-d25d-47ed-86ed-7e8c1381dad4)

## Result
Thus ,the program has been executed successfully

---

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1.Assign the string "google" to a variable.

2.Reverse the string manually using slicing ([::-1]).

3.Compare the original string with the reversed string.
- If they are equal, print that the string is a palindrome.
- Otherwise, print that it is not a palindrome.

4.Execute the program.
  
## 🧾 Program
```python
def palindrome(a):
    rev=str(a)[::-1]
    if a==rev:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)
```

## Output
![444008902-aadad268-65ba-43dd-a5f4-4c93e9e55dcc](https://github.com/user-attachments/assets/b008e2ae-9544-4067-b16a-475fb782c080)

## Result
Thus,the program has been executed successfully.

---

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## 🧠 Algorithm
1.Define a tuple x with some letters and numbers.

2.Use the in operator to check if the string 'n' exists within the tuple.

3.Use the in operator to check if the integer 8 exists within the tuple.

4.Print the results.

## 🧾 Program
```python
k=eval(input())
if "n" in k:
    print("False")
else:
    print("True")
if "8" in k:
    print("True")
else:
    print("False")
```
## Output
![444009667-26306f47-5d42-4dda-b173-9bfd66547178](https://github.com/user-attachments/assets/7c69a6ac-9766-4c57-bd8f-c7cb7403d544)

## Result
Thus,the program has been executed successfully.
