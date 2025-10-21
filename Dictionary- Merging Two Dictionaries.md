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
dict1 = eval(input())
dict2 = eval(input())
def merge():
    merged = {**dict1, **dict2}
    print("Merged dictionary:", merged)
merge()
```

## Output
<img width="1838" height="282" alt="image" src="https://github.com/user-attachments/assets/84bb54af-1721-4d74-804a-a853ae3b114e" />


## Result
Thus, the Python program that merges **two dictionaries** and combines their key-value pairs has been executed successfully.

