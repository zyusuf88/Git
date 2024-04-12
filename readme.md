# Version Control
Version control is a system that records changes to files over time, allowing you to recall specific versions later. <br> 
It helps manage collaboration among multiple contributors, track changes, and revert to previous versions if needed.

## Git
 Git is a popular version control system used to track changes in files. It's distributed, meaning every user has a complete copy of the repository, including its full history. <br> 
Git allows collaboration, branching, merging, and facilitates working on different features concurrently.

### git init: 

``` git init: ``` Transform the current directory into a Git repository
``` git init <directory>:``` Transform a directory in the current path into a Git repository


### git status:  
 Show the current status of the repository, including tracked/untracked files and changes.

### git add: 

Add changes in the working directory to the staging area. 
<br>
*You can add specific files by :*
```
git add file1 
```
*Or all files:* 
```
git add .
```

### git commit: 

Record changes staged in the index to the repository.
<br> *Example:*

```
git commit -m "First commit"
```

# git log vs git diff 
* The git log command displays committed snapshots. It lets you list the project history, filter it, and search for specific changes. 
<br>
![Screenshot of git log](git%20log%20picture.png)

* Whereas git diff show changes between commits, commit and working tree, etc.
<br>
![screenshot of git diff](git%20diff%20picture.png)


# .gitignore

`.gitignore` is a file where you specify intentionally untracked files to be ignored by Git. It helps avoid cluttering the repository with files like compiled binaries, logs, and temporary files. 
<br> Using `.gitignore` ensures that these files are not accidentally committed to the repository, improving its cleanliness and performance.

# Loops

Loops are control structures in programming that execute a block of code repeatedly as long as a specified condition is true. They are used to automate repetitive tasks and iterate over collections of data.

### There are mainly two types of loops:

1. **For Loop:** Used to iterate over a sequence (such as a list, tuple, or string) a fixed number of times.

2. **While Loop:** Executes a block of code as long as a specified condition is true. It's typically used when the number of iterations is not known beforehand.

## What is a For loop?

A for loop is used to iterate over a sequence (such as a list, tuple, or string) a fixed number of times. Here's an example of a for loop in Python:

```python
for i in range(10):
    print(i)
``` 

# **However**.....
Infinite loops occur when the loop condition always evaluates to true, causing the loop to run indefinitely. It's important to ensure that the loop condition eventually becomes false to avoid infinite looping.

1. Make sure that the loop condition will eventually evaluate to false to **prevent infinite loops**. 
<br>
```python
num = 0
while num < 5:
    print(num)
    num += 1
   ```
    
2. Maintain a **concise loop** body to minimize unnecessary iterations and enhance performance. 
<br>
``` python
for i in range(5):
    print(i)
   ```
3. **Selecting the suitable loop type:** Choose between for and while loops based on the specific needs of the task.
<br>
``` python 
names = ["Alice", "Bob", "Charlie"]
index = 0
while index < len(names):
    print(names[index])
    index += 1
```



