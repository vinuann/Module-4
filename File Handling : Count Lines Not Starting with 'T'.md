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

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    f1=open(file1_path,"r")
    f2=open(file2_path,"r")
    f3=open(output_file_path,"w")
    f3.write(f1.read())
    f3.write(f2.read())
    


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

```

## Output
<img width="1040" height="449" alt="image" src="https://github.com/user-attachments/assets/7193607c-cde7-41aa-b64f-a94af99a10a8" />

## Result
Thus, the program to merge two files into a third file using File Handling in Python was executed successfully
