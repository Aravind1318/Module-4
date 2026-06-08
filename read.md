# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def mech(r):
        a=3.1416*(r**2)
        a=round(a,2)
        print("Area of circle:",a)
r=int(input())
cse.mech(r)
```
## Output
<img width="236" height="50" alt="image" src="https://github.com/user-attachments/assets/225a4e7b-60c2-4446-ad20-35aca59b2fbe" />

## Result
Thus, the program has been executed successfully
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge(d1, d2):
    return {**d1, **d2}

print(merge(dict1, dict2))
```

## Output
<img width="343" height="47" alt="image" src="https://github.com/user-attachments/assets/5e945a83-7e66-4c66-86a9-b00ed5ad76a7" />

## Result
Thus, the program has been executed successfully.
# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
data = {'apple': 5, 'orange': 2, 'banana': 8, 'grape': 1}

sorted_by_keys = dict(sorted(data.items()))

sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original:", data)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="708" height="83" alt="image" src="https://github.com/user-attachments/assets/4fbc9ba7-88e6-4885-9a41-26c2adf9655c" />

## Result
Thus, the program has been executed successfully.
# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output
<img width="396" height="280" alt="image" src="https://github.com/user-attachments/assets/2c89ed4b-7507-4e36-9516-f47df3790578" />

## Result
Thus, the program has been executed successfully.
# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
   ```
def create_file(file_path,file_content):
    with open(file_path,'w') as f:
        f.write(file_content)
def count_words_in_file(file_path):
    with open(file_path,'r') as f:
        data=f.read()
        word=data.split()
        return len(word)
```
## Output
<img width="1433" height="515" alt="image" src="https://github.com/user-attachments/assets/8293c6bf-847b-4fee-8b83-d0a19bb5abe0" />

## Result
Thus, the program has been executed successfully.
