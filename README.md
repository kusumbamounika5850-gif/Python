<h1>🐍 Python Skills Portfolio</h1>
<p><strong>Fundamentals Overview</strong></p>

<p>
This document outlines my practical experience and theoretical understanding of essential
Python programming concepts. It is structured for clarity, quick review, and portfolio presentation.
</p>

<hr>

<h2>📌 I. Python Fundamentals</h2>

<h2>1️⃣ Core Data Types and Variables</h2>

<h3>🔹 Data Types</h3>
<p><strong>Definition:</strong><br>
Data types classify the kind of data a variable can store.

</p>

<ul>
  <li>🔢 <strong>int</strong> – Whole numbers (e.g., counting items)</li>
  <li>📐 <strong>float</strong> – Decimal numbers (e.g., prices, measurements)</li>
  <li>📝 <strong>str</strong> – Text data (e.g., names, messages)</li>
  <li>✅ <strong>bool</strong> – Logical values (<code>True</code> or <code>False</code>)</li>
</ul>

<p><strong>Key Characteristics:</strong></p>
<ul>
  <li>Python is <strong>dynamically typed</strong>.</li>
  <li>Data types are determined during program execution.</li>
</ul>

<p><strong>Examples:</strong></p>
<ul>
  <li>User age stored as an integer</li>
  <li>Product price stored as a float</li>
  <li>Username stored as a string</li>
  <li>Login status stored as a boolean</li>
</ul>

<hr>

<h3>🔹 Variables</h3>
<p><strong>Definition:</strong><br>
Variables are named storage locations used to hold data values.
</p>

<ul>
  <li>Created automatically when a value is assigned</li>
  <li>No explicit type declaration required</li>
  <li>Values can change during execution</li>
</ul>

<p><strong>Examples:</strong></p>
<ul>
  <li>Storing a student's score</li>
  <li>Updating a counter value</li>
</ul>

<hr>

<h3>🔹 Type Conversion (Casting)</h3>
<p><strong>Definition:</strong><br>
Type conversion is the process of changing one data type into another.
</p>

<ul>
  <li><code>int()</code> – Convert to integer</li>
  <li><code>float()</code> – Convert to decimal number</li>
  <li><code>str()</code> – Convert to string</li>
  <li><code>list()</code>, <code>tuple()</code> – Convert to collections</li>
</ul>

<p><strong>Why It’s Important:</strong></p>
<ul>
  <li>Required when mixing data types</li>
  <li>Prevents runtime errors</li>
</ul>

<p><strong>Examples:</strong></p>
<ul>
  <li>Converting user input into a number</li>
  <li>Displaying numbers as text in messages</li>
</ul>

<hr>

<h2>2️⃣ Operators and Expressions</h2>
<p>
Operators are symbols that perform operations on variables and values.
</p>

<h3>➕ Arithmetic Operators</h3>
<table>
  <tr><th>Operator</th><th>Description</th></tr>
  <tr><td>+</td><td>Addition</td></tr>
  <tr><td>-</td><td>Subtraction</td></tr>
  <tr><td>*</td><td>Multiplication</td></tr>
  <tr><td>/</td><td>Division</td></tr>
  <tr><td>%</td><td>Modulus</td></tr>
  <tr><td>**</td><td>Exponentiation</td></tr>
  <tr><td>//</td><td>Floor Division</td></tr>
</table>

<h3>⚖️ Comparison Operators</h3>
<table>
  <tr><th>Operator</th><th>Meaning</th></tr>
  <tr><td>==</td><td>Equal to</td></tr>
  <tr><td>!=</td><td>Not equal to</td></tr>
  <tr><td>&gt;</td><td>Greater than</td></tr>
  <tr><td>&lt;</td><td>Less than</td></tr>
  <tr><td>&gt;=</td><td>Greater than or equal to</td></tr>
  <tr><td>&lt;=</td><td>Less than or equal to</td></tr>
</table>

<h3>🔗 Logical Operators</h3>
<ul>
  <li><strong>and</strong> – All conditions must be true</li>
  <li><strong>or</strong> – At least one condition must be true</li>
  <li><strong>not</strong> – Reverses a condition</li>
</ul>

<h3>📝 Assignment Operators</h3>
<ul>
  <li><code>=</code> Assign value</li>
  <li><code>+=</code> Add and assign</li>
  <li><code>-=</code> Subtract and assign</li>
  <li><code>*=</code> Multiply and assign</li>
</ul>

<h3>🧠 Identity Operators</h3>
<ul>
  <li><code>is</code> – Same memory location</li>
  <li><code>is not</code> – Different memory locations</li>
</ul>

<h3>📦 Membership Operators</h3>
<ul>
  <li><code>in</code> – Value exists in a sequence</li>
  <li><code>not in</code> – Value does not exist in a sequence</li>
</ul>

<hr>

<h1>📘 Python Built-in Functions, Libraries & Data Structures</h1>

<hr>

<h2>3. Built-in Functions and Libraries</h2>

<h3>🔹 Built-in Functions</h3>
<p><strong>Definition:</strong><br>
Built-in functions are functions that are <strong>always available in Python</strong>. 
They can be used <strong>without importing any module</strong> and provide core functionality.</p>

<ul>
  <li>🖨️ <strong>print()</strong> – Displays output</li>
  <li>📏 <strong>len()</strong> – Returns number of elements</li>
  <li>🔍 <strong>type()</strong> – Returns data type</li>
  <li>🔢 <strong>range()</strong> – Generates a sequence of numbers</li>
  <li>⬆️ <strong>max()</strong> / ⬇️ <strong>min()</strong> – Finds maximum or minimum value</li>
</ul>

<pre><code>
print("Hello, Python")
len("Python")
type(10)
list(range(1,5))
max([4, 8, 2])
</code></pre>

---

<h3>🔹 Libraries (Modules)</h3>
<p><strong>Definition:</strong><br>
Libraries (or modules) are <strong>collections of pre-written code</strong> that extend Python’s functionality.
They must be imported before use.</p>

<ul>
  <li>📐 <strong>math</strong> – Mathematical operations</li>
  <li>🎲 <strong>random</strong> – Random number generation</li>
  <li>🗂️ <strong>os</strong> – Operating system interaction</li>
</ul>

<pre><code>
import math
math.sqrt(16)

import random
random.randint(1, 10)

import os
os.getcwd()
</code></pre>

<hr>

<h2>4. Sequence and Mapping Data Structures</h2>

<h2>4.1 String (<code>str</code>) – Immutable Sequence of Characters</h2>

<p><strong>Definition:</strong><br>
A string is a sequence of characters enclosed in quotes. 
Strings are <strong>immutable</strong>, meaning their content cannot be changed after creation.</p>

<h3>✨ String Methods</h3>

<table>
  <tr>
    <th>Category</th>
    <th>Methods</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>🔠 Formatting</td>
    <td>upper(), lower(), capitalize(), title()</td>
    <td>Change text case</td>
  </tr>
  <tr>
    <td>🔍 Searching</td>
    <td>find(), index(), count()</td>
    <td>Find substrings</td>
  </tr>
  <tr>
    <td>✅ Checking</td>
    <td>isalpha(), isdigit(), isalnum(), isspace()</td>
    <td>Validate string content</td>
  </tr>
  <tr>
    <td>✂️ Manipulation</td>
    <td>strip(), lstrip(), rstrip()</td>
    <td>Remove whitespace</td>
  </tr>
  <tr>
    <td>🔗 Split / Join</td>
    <td>split(), join()</td>
    <td>Split or combine strings</td>
  </tr>
  <tr>
    <td>🔁 Replace</td>
    <td>replace()</td>
    <td>Replace substring</td>
  </tr>
</table>

<pre><code>
text = "hello world"
text.upper()
text.find("world")
text.isalpha()
text.strip()
text.split(" ")
"-".join(["2025","01","10"])
text.replace("world", "Python")
</code></pre>

<hr>

<h2>4.2 List (<code>list</code>) – Mutable Ordered Sequence</h2>

<p><strong>Definition:</strong><br>
A list is a mutable and ordered collection of elements. 
Items can be added, removed, or modified.</p>

<h3>📋 List Methods</h3>

<table>
  <tr>
    <th>Category</th>
    <th>Methods</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>➕ Adding</td>
    <td>append(), insert(), extend()</td>
    <td>Add elements to list</td>
  </tr>
  <tr>
    <td>➖ Removing</td>
    <td>remove(), pop(), clear()</td>
    <td>Remove elements</td>
  </tr>
  <tr>
    <td>🔃 Ordering</td>
    <td>sort(), reverse()</td>
    <td>Reorder list</td>
  </tr>
  <tr>
    <td>🔎 Querying</td>
    <td>index(), count()</td>
    <td>Search list</td>
  </tr>
  <tr>
    <td>📄 Copying</td>
    <td>copy()</td>
    <td>Create shallow copy</td>
  </tr>
</table>

<pre><code>
nums = [1, 2, 3]
nums.append(4)
nums.insert(1, 10)
nums.extend([5, 6])
nums.remove(10)
nums.pop()
nums.sort()
nums.reverse()
nums.copy()
</code></pre>

<hr>

<h2>📌 4.3 Tuple (<code>tuple</code>) — Immutable, Ordered Sequence</h2>

<h3>🔹 Definition</h3>
<p>
A <strong>tuple</strong> is an <strong>ordered collection</strong> of elements that
<strong>cannot be changed (immutable)</strong> after creation.
Tuples are <strong>faster than lists</strong> and can be used as
<strong>dictionary keys</strong> if they contain only hashable items.
</p>

<h3>🔹 Key Characteristics</h3>
<ul>
  <li>🔒 <strong>Immutable</strong> (cannot modify elements)</li>
  <li>📍 <strong>Ordered</strong> (index-based access)</li>
  <li>⚡ <strong>Efficient &amp; memory-friendly</strong></li>
  <li>🔑 Can be used as <strong>dictionary keys</strong></li>
</ul>

<h3>🔹 Common Methods</h3>

<pre><code>t = (1, 2, 3, 2)

t.index(2)   # 1 → first position of value 2
t.count(2)   # 2 → number of times 2 appears
</code></pre>

<h3>🔹 Built-in Functions</h3>

<pre><code>len(t)       # 4 → total elements
sorted(t)    # [1, 2, 2, 3] → returns a LIST
</code></pre>

<hr>

<h2>📌 4.4 Set (<code>set</code>) — Mutable, Unordered Collection of Unique Items</h2>

<h3>🔹 Definition</h3>
<p>
A <strong>set</strong> is an <strong>unordered collection</strong> that stores
<strong>only unique elements</strong>. It is optimized for
<strong>fast membership testing</strong> and
<strong>mathematical set operations</strong>.
</p>

<h3>🔹 Key Characteristics</h3>
<ul>
  <li>🔁 <strong>Mutable</strong> (can add/remove elements)</li>
  <li>❌ <strong>No duplicate values</strong></li>
  <li>🚀 <strong>Fast lookup</strong></li>
  <li>🔢 <strong>No indexing</strong></li>
</ul>

<h3>🔹 Adding &amp; Removing Elements</h3>

<pre><code>s = {1, 2, 3}

s.add(4)        # {1, 2, 3, 4}
s.remove(2)     # removes 2 (error if not found)
s.discard(5)    # no error if element not found
s.pop()         # removes an arbitrary element
s.clear()       # empties the set
</code></pre>

<h3>🔹 Set Operations</h3>

<pre><code>a = {1, 2, 3}
b = {3, 4, 5}

a.union(b)                  # {1, 2, 3, 4, 5}
a.intersection(b)           # {3}
a.difference(b)             # {1, 2}
a.symmetric_difference(b)   # {1, 2, 4, 5}
</code></pre>

<h3>🔹 Set Comparisons</h3>

<pre><code>a.issubset(b)
a.issuperset(b)
a.isdisjoint(b)
</code></pre>

<hr>

<h2>📌 4.5 Dictionary (<code>dict</code>) — Mutable Mapping of Key-Value Pairs</h2>

<h3>🔹 Definition</h3>
<p>
A <strong>dictionary</strong> stores data as <strong>key–value pairs</strong>, where
<strong>keys are unique and immutable</strong>, and values can be any data type.
Dictionaries are <strong>highly efficient</strong> for data retrieval.
</p>

<h3>🔹 Key Characteristics</h3>
<ul>
  <li>🔑 <strong>Unique keys</strong></li>
  <li>🔄 <strong>Mutable</strong></li>
  <li>⚡ <strong>Fast lookup</strong></li>
  <li>🧩 <strong>Stores data in key–value pairs</strong></li>
</ul>

<h3>🔹 Accessing Data</h3>

<pre><code>d = {"name": "Alice", "age": 25}

d.get("age")           # 25
d.get("salary", 0)     # 0 (avoids KeyError)

d.keys()               # dict_keys(['name', 'age'])
d.values()             # dict_values(['Alice', 25])
d.items()              # dict_items([('name', 'Alice'), ('age', 25)])
</code></pre>

<h3>🔹 Modifying Dictionary</h3>

<pre><code>d.update({"age": 26, "city": "Paris"})
d.pop("age")           # removes key and returns value
d.popitem()            # removes last inserted item

d.setdefault("country", "France")
</code></pre>

<h3>🔹 Creating a Dictionary</h3>

<pre><code>dict.fromkeys(["a", "b", "c"], 0)
# {'a': 0, 'b': 0, 'c': 0}
</code></pre>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Python Control Flow & Functions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        code {
            background-color: #eaeaea;
            padding: 2px 6px;
            border-radius: 4px;
        }
        pre {
            background-color: #eaeaea;
            padding: 10px;
            border-radius: 6px;
            overflow-x: auto;
        }
        .icon {
            font-weight: bold;
            margin-right: 8px;
        }
        ul {
            margin-bottom: 20px;
        }
        li {
            margin-bottom: 8px;
        }
    </style>
</head>
<body>

<h1>🧭 Python Control Flow & Functions</h1>

<p>Control flow determines <strong>the order in which a program’s instructions are executed</strong>. It allows a program to <strong>make decisions</strong> and <strong>repeat actions</strong> when needed.</p>

<h2>🔹 1. Conditional Statements</h2>
<p>Conditional statements help a program <strong>decide what to do</strong> based on conditions that are either <strong>True</strong> or <strong>False</strong>.</p>

<h3>✅ if / elif / else</h3>
<p>Used to <strong>check conditions</strong> and execute different blocks of code.</p>
<ul>
    <li><code>if</code> → checks the first condition</li>
    <li><code>elif</code> → checks another condition if the previous one is false</li>
    <li><code>else</code> → runs when all conditions are false</li>
</ul>

<pre><code>age = 18

if age &lt; 18:
    print("You are a minor.")
elif age == 18:
    print("You just became an adult!")
else:
    print("You are an adult.")</code></pre>

<h3>⛔ break</h3>
<p>Used <strong>inside loops only</strong> (<code>for</code> or <code>while</code>). It <strong>immediately stops the loop</strong>.</p>

<pre><code>for number in range(1, 6):
    if number == 3:
        break
    print(number)</code></pre>

<p>Output:</p>
<pre><code>1
2</code></pre>

<h2>🔁 2. Control Statements (Loops)</h2>
<p>Loops allow code to <strong>run repeatedly</strong> without writing it again and again.</p>

<h3>🔄 for Loop</h3>
<p>Used when you <strong>know how many times</strong> you want to loop. Works with lists, strings, ranges, tuples, etc.</p>

<pre><code>for item in [1, 2, 3]:
    print(item)</code></pre>

<p>Output:</p>
<pre><code>1
2
3</code></pre>

<h3>🔂 while Loop</h3>
<p>Used when the number of repetitions is <strong>unknown</strong>. Runs <strong>as long as a condition remains True</strong>.</p>

<pre><code>count = 0
while count &lt; 5:
    print(count)
    count += 1</code></pre>

<p>Output:</p>
<pre><code>0
1
2
3
4</code></pre>

<h2>🧠 III. Functions and Advanced Techniques</h2>

<h3>🔹 1. Defining and Using Functions</h3>
<p>A <strong>function</strong> is a reusable block of code that performs a specific task.</p>

<h4>🧩 def Keyword</h4>
<p>Used to <strong>define a function</strong>. Functions make code <strong>organized, reusable, and readable</strong>.</p>

<pre><code>def greet(name):
    """This function greets the person passed in as a parameter."""
    return f"Hello, {name}!"</code></pre>

<p>Usage:</p>
<pre><code>print(greet("Alex"))</code></pre>

<p>Output:</p>
<pre><code>Hello, Alex!</code></pre>

<h3>🔁 Recursion: Solving Problems by Self-Reference</h3>
<p>Recursion is when a <strong>function calls itself</strong> to solve a problem.</p>

<h4>🧱 Key Components</h4>
<ul>
    <li><strong>Base Case:</strong> Stops the recursion to prevent infinite loops.</li>
    <li><strong>Recursive Step:</strong> Calls the function again with a smaller/simpler input.</li>
</ul>

<h4>📐 Example: Factorial</h4>
<p>The factorial of a number <code>n</code> is:</p>
<pre><code>n! = n × (n−1)!
0! = 1</code></pre>

<pre><code>def factorial(n):
    # Base Case
    if n == 0:
        return 1
    # Recursive Step
    else:
        return n * factorial(n - 1)</code></pre>

<p>Example Call:</p>
<pre><code>factorial(4)</code></pre>

<p>Step by step:</p>
<pre><code>4 × factorial(3)
4 × (3 × factorial(2))
4 × (3 × (2 × factorial(1)))
4 × (3 × (2 × (1 × factorial(0))))
4 × (3 × (2 × (1 × 1)))
= 24</code></pre>

<h1>📌 Advantages and Disadvantages of Recursion</h1>

<table>
  <thead>
    <tr>
      <th>Aspect</th>
      <th>Advantage ✅</th>
      <th>Disadvantage ❌</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Readability</td>
      <td>Leads to cleaner, more intuitive code for problems naturally defined recursively (e.g., tree traversals, mathematical sequences).</td>
      <td></td>
    </tr>
    <tr>
      <td>Complexity</td>
      <td></td>
      <td>Can be harder to trace and debug than iterative solutions.</td>
    </tr>
    <tr>
      <td>Performance</td>
      <td></td>
      <td>Each recursive call adds a new stack frame, consuming more memory and potentially slowing execution.</td>
    </tr>
  </tbody>
</table>

<h1>🌟 Functional Programming Concepts</h1>
<p>Functional programming lets you write <strong>concise, expressive code</strong>, often when working with <strong>iterables</strong>.</p>

<h2>1️⃣ Lambda Functions</h2>
<p><strong>Definition:</strong> Small, anonymous functions defined using <code>lambda</code>.</p>
<p><strong>Characteristics:</strong> Can take any number of arguments but only one expression.</p>
<p><strong>Usage:</strong> Often used as arguments to higher-order functions like <code>map</code> and <code>filter</code>.</p>

<pre><code># Lambda function to square a number
square = lambda x: x * x
print(square(5))  # Output: 25
</code></pre>

<h2>2️⃣ map()</h2>
<p><strong>Definition:</strong> Applies a function to every item of an iterable and returns an iterator.</p>
<p><strong>Usage:</strong> Transforming data.</p>

<pre><code>numbers = [1, 2, 3, 4]
squared = list(map(lambda x: x**2, numbers))
print(squared)  # Output: [1, 4, 9, 16]
</code></pre>

<h2>3️⃣ filter()</h2>
<p><strong>Definition:</strong> Constructs an iterator from elements of an iterable for which a function returns True.</p>
<p><strong>Usage:</strong> Selecting a subset of data.</p>

<pre><code>numbers = [1, 2, 3, 4, 5, 6]
even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
print(even_numbers)  # Output: [2, 4, 6]
</code></pre>

<h2>4️⃣ reduce() (from functools)</h2>
<p><strong>Definition:</strong> Applies a function cumulatively to items of an iterable, reducing it to a single value.</p>
<p><strong>Usage:</strong> Aggregation.</p>

<pre><code>from functools import reduce

numbers = [1, 2, 3, 4]
sum_total = reduce(lambda x, y: x + y, numbers)
print(sum_total)  # Output: 10
</code></pre>

<h1>🧩 Comprehensions</h1>
<p><strong>Definition:</strong> Concise, readable, and efficient way to create data structures. Preferred over loops for simple creation tasks.</p>

<h2>1️⃣ List Comprehensions</h2>
<pre><code># Creating a list of squares
squares = [x**2 for x in range(10)]
print(squares)  # Output: [0, 1, 4, 9, ..., 81]

# List with condition
even_squares = [x**2 for x in range(10) if x % 2 == 0]
print(even_squares)  # Output: [0, 4, 16, 36, 64]
</code></pre>

<h2>2️⃣ Dictionary Comprehensions</h2>
<pre><code>names = ['Alice', 'Bob', 'Charlie']
name_lengths = {name: len(name) for name in names}
print(name_lengths)  # Output: {'Alice': 5, 'Bob': 3, 'Charlie': 7}
</code></pre>

<p>✅ <strong>Tip:</strong> Use recursion for naturally recursive problems, functional tools for concise data manipulation, and comprehensions for readable, one-liner data creation.</p>

<hr>

<h2>📁 FILE HANDLING IN PYTHON</h2>
<p>File handling is used to <b>create, read, write, and append</b> data in files.</p>

<h3>✍️ Write Mode (<code>w</code>)</h3>
<p><b>Definition:</b> Creates a new file or overwrites an existing file.</p>

<pre><code>
file = open("data.txt", "w")
file.write("Hello Python")
file.close()
</code></pre>

<ul>
  <li>If file exists → old data is deleted</li>
  <li>If file does not exist → new file is created</li>
</ul>

<hr>

<h3>➕ Append Mode (<code>a</code>)</h3>
<p><b>Definition:</b> Adds data at the end of the file.</p>

<pre><code>
file = open("data.txt", "a")
file.write("\nWelcome to file handling")
file.close()
</code></pre>

<p>✔ Old data remains safe</p>

<hr>

<h3>📖 Read Mode (<code>r</code>)</h3>
<p><b>Definition:</b> Reads data from an existing file.</p>

<pre><code>
file = open("data.txt", "r")
print(file.read())
file.close()
</code></pre>

<p>⚠️ Error if file does not exist</p>

<hr>

<h2>🧾 JSON FILE HANDLING</h2>
<p>JSON stands for <b>JavaScript Object Notation</b>.  
It is used for data storage and exchange.</p>

<h3>💾 json.dump()</h3>
<p><b>Definition:</b> Writes Python data into a JSON file.</p>

<pre><code>
import json

data = {"name": "Rahul", "age": 22}

with open("data.json", "w") as file:
    json.dump(data, file)
</code></pre>

<hr>

<h3>📂 json.load()</h3>
<p><b>Definition:</b> Reads data from a JSON file.</p>

<pre><code>
import json

with open("data.json", "r") as file:
    data = json.load(file)

print(data)
</code></pre>

<hr>

<h3>🔄 json.dumps()</h3>
<p><b>Definition:</b> Converts Python object into a JSON string.</p>

<pre><code>
import json

data = {"city": "Delhi"}
json_string = json.dumps(data)
print(json_string)
</code></pre>

<hr>

<h3>🔁 json.loads()</h3>
<p><b>Definition:</b> Converts JSON string into Python object.</p>

<pre><code>
import json

json_string = '{"city": "Delhi"}'
data = json.loads(json_string)
print(data)
</code></pre>

<hr>

<h2>⚠️ EXCEPTION HANDLING IN PYTHON</h2>
<p>Exceptions are runtime errors that stop program execution.</p>

<h3>❌ SyntaxError</h3>
<p><b>Definition:</b> Incorrect Python syntax.</p>

<pre><code>
print("Hello"
</code></pre>

<hr>

<h3>➗ ZeroDivisionError</h3>
<p><b>Definition:</b> Division by zero.</p>

<pre><code>
print(10 / 0)
</code></pre>

<hr>

<h3>🔤 NameError</h3>
<p><b>Definition:</b> Variable not defined.</p>

<pre><code>
print(x)
</code></pre>

<hr>

<h3>🔢 ValueError</h3>
<p><b>Definition:</b> Correct type but invalid value.</p>

<pre><code>
int("abc")
</code></pre>

<hr>

<h3>📁 FileNotFoundError</h3>
<p><b>Definition:</b> File does not exist.</p>

<pre><code>
open("missing.txt", "r")
</code></pre>

<hr>

<h3>📐 IndentationError</h3>
<p><b>Definition:</b> Incorrect indentation.</p>

<pre><code>
if True:
print("Hello")
</code></pre>

<hr>

<h2>🛡️ Try–Except Example</h2>

<pre><code>
try:
    print(10 / 0)
except ZeroDivisionError:
    print("Cannot divide by zero")
</code></pre>

<hr>

<h2>📊 SUMMARY</h2>

<table border="1" cellpadding="8">
  <tr>
    <th>Topic</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>w</td>
    <td>Write / Overwrite</td>
  </tr>
  <tr>
    <td>a</td>
    <td>Append Data</td>
  </tr>
  <tr>
    <td>r</td>
    <td>Read File</td>
  </tr>
  <tr>
    <td>dump / load</td>
    <td>JSON File Handling</td>
  </tr>
  <tr>
    <td>dumps / loads</td>
    <td>JSON String Handling</td>
  </tr>
  <tr>
    <td>Exceptions</td>
    <td>Error Handling</td>
  </tr>
</table>

<hr>
<h1 align="center">🐍 OOPS Concepts in Python</h1>
<hr>

<h2>🧱 Class</h2>
<p>
<b>Definition:</b> A class is a blueprint or template used to create objects.  
It defines variables and methods.
</p>

<pre><code>
class Student:
    pass
</code></pre>

<hr>

<h2>🧸 Object</h2>
<p>
<b>Definition:</b> An object is an instance of a class.
</p>

<pre><code>
s1 = Student()
</code></pre>

<hr>

<h2>🔑 self</h2>
<p>
<b>Definition:</b> <code>self</code> refers to the current object of the class.  
It is used to access variables and methods inside the class.
</p>

<pre><code>
class Student:
    def show(self):
        print("Hello Student")
</code></pre>

<hr>

<h2>🛠️ Constructor (__init__) and Types</h2>

<h3>🔹 Default Constructor</h3>
<pre><code>
class Student:
    def __init__(self):
        print("Default Constructor")
</code></pre>

<h3>🔹 Parameterized Constructor</h3>
<pre><code>
class Student:
    def __init__(self, name):
        self.name = name

s1 = Student("Amit")
</code></pre>

<hr>

<h2>📦 Variables and Functions in Class</h2>

<h3>🔹 Variables</h3>
<ul>
  <li><b>Instance Variable</b> – Specific to object</li>
  <li><b>Class Variable</b> – Common to all objects</li>
</ul>

<pre><code>
class Student:
    college = "ABC College"

    def __init__(self, name):
        self.name = name
</code></pre>

<h3>🔹 Functions (Methods)</h3>
<pre><code>
class Student:
    def show(self):
        print("This is a method")
</code></pre>

<hr>

<h2>🧬 Inheritance</h2>
<p>
<b>Definition:</b> Inheritance allows a child class to acquire properties and methods of a parent class.
</p>

<pre><code>
class Parent:
    def show(self):
        print("Parent class")

class Child(Parent):
    pass

c = Child()
c.show()
</code></pre>

<hr>

<h2>🎭 Polymorphism</h2>
<p>
<b>Definition:</b> Polymorphism means one method name with different behaviors.
</p>

<pre><code>
class Bird:
    def sound(self):
        print("Bird makes sound")

class Dog(Bird):
    def sound(self):
        print("Dog barks")

d = Dog()
d.sound()
</code></pre>

<hr>

<h2>🧠 Abstraction</h2>
<p>
<b>Definition:</b> Abstraction hides implementation details and shows only essential features.
</p>

<pre><code>
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

class Square(Shape):
    def area(self):
        print("Area of square")
</code></pre>

<hr>

<h2>🔒 Encapsulation</h2>
<p>
<b>Definition:</b> Encapsulation binds data and methods together and restricts direct access.
</p>

<pre><code>
class Account:
    def __init__(self):
        self.__balance = 1000

    def show_balance(self):
        print(self.__balance)
</code></pre>

<hr>

<h2>🌟 Summary</h2>

<table border="1" cellpadding="8">
<tr>
  <th>Icon</th>
  <th>Concept</th>
  <th>Meaning</th>
</tr>
<tr>
  <td>🧱</td>
  <td>Class</td>
  <td>Blueprint</td>
</tr>
<tr>
  <td>🧸</td>
  <td>Object</td>
  <td>Instance of class</td>
</tr>
<tr>
  <td>🔑</td>
  <td>self</td>
  <td>Current object</td>
</tr>
<tr>
  <td>🧬</td>
  <td>Inheritance</td>
  <td>Parent → Child</td>
</tr>
<tr>
  <td>🎭</td>
  <td>Polymorphism</td>
  <td>Many forms</td>
</tr>
<tr>
  <td>🧠</td>
  <td>Abstraction</td>
  <td>Hide details</td>
</tr>
<tr>
  <td>🔒</td>
  <td>Encapsulation</td>
  <td>Data protection</td>
</tr>
</table>
<h1>🏭 Production Python: 
  
Multiprocessing vs Multithreading</h1>

<p>
In <strong>production Python</strong>, choosing between
<strong>multithreading</strong> and <strong>multiprocessing</strong> impacts:
</p>

<ul>
  <li>⚡ Performance</li>
  <li>🧠 CPU utilization</li>
  <li>🔒 Stability & isolation</li>
  <li>📈 Scalability</li>
</ul>

<p>
The <strong>GIL (Global Interpreter Lock)</strong> is the key reason this decision matters.
</p>

<hr/>

<h2>🧵 Multithreading</h2>

<h3>🧩 Definition</h3>
<p>
<strong>Multithreading</strong> runs multiple threads within the <strong>same process</strong>,
sharing the same memory space.
</p>

<blockquote>
In Python, threads do <strong>NOT</strong> run CPU-bound code in parallel due to the GIL.
</blockquote>

<h3>🎯 Best For</h3>
<ul>
  <li>✅ I/O-bound tasks</li>
  <li>🌐 Network calls</li>
  <li>📁 File I/O</li>
  <li>🔌 API requests</li>
  <li>🗄️ Database queries</li>
</ul>

<h3>🧠 Mental Model</h3>
<p>
🧑‍💻 One brain (CPU)<br/>
👥 Many hands (threads)<br/>
⛔ Only one hand thinks at a time (GIL)
</p>

<h3>🧪 Example (I/O-Bound)</h3>

<pre><code class="language











