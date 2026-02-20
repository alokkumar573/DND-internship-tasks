Day 1 : Python Setup, Variables & Data Types
🔹 Python Installation & Setup
Python is a high-level, easy-to-learn programming language.
Download from official website managed by
 Python Software Foundation


Install and check:


python --version
If installed correctly, it shows the version.

🔹 Variables
Variables store data in memory.
Python is dynamically typed (no need to declare data type).


Variable names should start with a letter or underscore.


Case-sensitive.


x = 10
name = "Alex"

🔹 Basic Data Types
1. Integer (int) → Whole numbers
x = 10
2. Float (float) → Decimal numbers
y = 3.5
3. String (str) → Text data
name = "Alex"
4. Boolean (bool) → True or False
flag = True
Use type() to check data type.

Day 2 : Lists, Dictionaries & Loops
🔹 List
A list is a built-in data structure in Python used to store multiple items in a single variable.
 Key Characteristics:
Ordered → Items have a fixed position (index starts from 0).


Mutable → You can modify, add, or remove elements.


Allows Duplicates → Same value can appear multiple times.


Can store different data types in one list.


lst = [1, 2, 3, "Alex", 4.5]



🔹 Dictionary 
A dictionary is a collection of data stored in key-value pairs.
It is used when data needs to be accessed using a unique key.
student = {
   "name": "Alex",
   "age": 20
}


🔹 Loops
for Loop
Used when number of iterations is known.
for i in lst:
   print(i)
while Loop
Runs until condition becomes False.
i = 0
while i < len(lst):
   print(lst[i])
   i += 1

🔹 List Comprehension
Short way to create lists.
squares = [x * x for x in range(5)]

🔹 Default Dictionary
From collections module.
 Gives default value if key not present.
from collections import defaultdict
d = defaultdict(int)
d["a"] += 1

🔹 Nested Structures
Nested List
matrix = [[1, 2], [3, 4]]
Nested Dictionary
student = {
   "name": "Alex",
   "marks": {"math": 80}
}

Day 3 : Functions, Modules & Lambda
🔹 Functions
Reusable block of code.
def add(a, b):
   return a + b
Benefits:
Avoid repetition


Improve readability



🔹 Modules
A module is a Python file with functions and variables.
Example:
import math
print(math.sqrt(16))

🔹 Lambda Function
Small one-line anonymous function.
square = lambda x: x * x
print(square(5))
Used with map(), filter(), etc.

Day 4 : Git Basics
🔹 What is Git?
Git is a version control system created by
 Linus Torvalds
It helps track code changes and manage projects.

🔹 Basic Commands
Initialize repository:
git init
Add files:
git add .
Commit changes:
git commit -m "First commit"
Push to remote repository like
 GitHub
git push origin main


