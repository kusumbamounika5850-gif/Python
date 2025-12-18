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




