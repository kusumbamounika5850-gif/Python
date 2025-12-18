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

<p align="center"><strong>🚀 Happy Coding with Python!</strong></p>


