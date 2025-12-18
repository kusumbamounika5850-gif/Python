<h1>I. Python Fundamentals</h1>

<h2>1. Core Data Types and Variables</h2>

<h3>Variables</h3>
<p>
A <strong>variable</strong> is a name that stores a value in memory.
Python automatically detects the data type.
</p>

<pre>
x = 10
name = "Alice"
</pre>

<ul>
  <li><code>x</code> stores an integer value</li>
  <li><code>name</code> stores a string value</li>
</ul>

<h3>Core Data Types</h3>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Data Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>int</td>
    <td>Whole numbers</td>
    <td>10, -5</td>
  </tr>
  <tr>
    <td>float</td>
    <td>Decimal numbers</td>
    <td>3.14, 2.0</td>
  </tr>
  <tr>
    <td>str</td>
    <td>Text data</td>
    <td>"Hello"</td>
  </tr>
  <tr>
    <td>bool</td>
    <td>Boolean values</td>
    <td>True, False</td>
  </tr>
  <tr>
    <td>list</td>
    <td>Ordered, changeable collection</td>
    <td>[1, 2, 3]</td>
  </tr>
  <tr>
    <td>tuple</td>
    <td>Ordered, unchangeable collection</td>
    <td>(1, 2, 3)</td>
  </tr>
  <tr>
    <td>set</td>
    <td>Unordered, unique values</td>
    <td>{1, 2, 3}</td>
  </tr>
  <tr>
    <td>dict</td>
    <td>Key-value pairs</td>
    <td>{"a": 1, "b": 2}</td>
  </tr>
</table>

<pre>
age = 25
price = 19.99
is_active = True
colors = ["red", "blue"]
</pre>

<hr>

<h2>2. Operators and Expressions</h2>

<p>
<strong>Operators</strong> are special symbols that perform operations on variables and values.
An <strong>expression</strong> is a combination of values and operators.
</p>

<h3>A. Arithmetic Operators</h3>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr><td>+</td><td>Addition</td><td>5 + 2</td></tr>
  <tr><td>-</td><td>Subtraction</td><td>5 - 2</td></tr>
  <tr><td>*</td><td>Multiplication</td><td>5 * 2</td></tr>
  <tr><td>/</td><td>Division</td><td>5 / 2</td></tr>
  <tr><td>%</td><td>Modulus</td><td>5 % 2</td></tr>
  <tr><td>**</td><td>Exponentiation</td><td>5 ** 2</td></tr>
  <tr><td>//</td><td>Floor Division</td><td>5 // 2</td></tr>
</table>

<pre>
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a ** b)
print(a // b)
</pre>

<h3>B. Comparison Operators</h3>

<p>Comparison operators compare values and return <strong>True</strong> or <strong>False</strong>.</p>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Description</th>
  </tr>
  <tr><td>==</td><td>Equal to</td></tr>
  <tr><td>!=</td><td>Not equal to</td></tr>
  <tr><td>&gt;</td><td>Greater than</td></tr>
  <tr><td>&lt;</td><td>Less than</td></tr>
  <tr><td>&gt;=</td><td>Greater than or equal to</td></tr>
  <tr><td>&lt;=</td><td>Less than or equal to</td></tr>
</table>

<pre>
x = 5
y = 10

print(x == y)
print(x != y)
print(x > y)
print(x < y)
print(x <= 5)
</pre>

<h3>C. Logical Operators</h3>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Description</th>
  </tr>
  <tr><td>and</td><td>True if both conditions are true</td></tr>
  <tr><td>or</td><td>True if at least one condition is true</td></tr>
  <tr><td>not</td><td>Reverses the result</td></tr>
</table>

<pre>
a = 5
b = 10

print(a > 3 and b > 5)
print(a > 6 or b > 5)
print(not (a > 3))
</pre>

<h3>D. Assignment Operators</h3>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Example</th>
    <th>Equivalent To</th>
  </tr>
  <tr><td>=</td><td>x = 5</td><td>Assign value</td></tr>
  <tr><td>+=</td><td>x += 2</td><td>x = x + 2</td></tr>
  <tr><td>-=</td><td>x -= 2</td><td>x = x - 2</td></tr>
  <tr><td>*=</td><td>x *= 2</td><td>x = x * 2</td></tr>
  <tr><td>/=</td><td>x /= 2</td><td>x = x / 2</td></tr>
</table>

<pre>
x = 10
x += 5
print(x)
</pre>

<h3>E. Identity Operators</h3>

<p>
Identity operators check whether two variables refer to the same object in memory.
</p>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Description</th>
  </tr>
  <tr><td>is</td><td>Same object</td></tr>
  <tr><td>is not</td><td>Different object</td></tr>
</table>

<pre>
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)
print(a is c)
print(a == c)
</pre>

<h3>F. Membership Operators</h3>

<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Operator</th>
    <th>Description</th>
  </tr>
  <tr><td>in</td><td>Value exists in sequence</td></tr>
  <tr><td>not in</td><td>Value does not exist</td></tr>
</table>

<pre>
numbers = [1, 2, 3, 4]

print(2 in numbers)
print(5 not in numbers)
</pre>

<pre>
text = "Python"

print("P" in text)
print("z" in text)
</pre>

<hr>

<h2>3. Built-in Functions and Libraries</h2>

<h3>Built-in Functions</h3>
<p>
<b>Definition:</b> Built-in functions are functions that are always available in Python
and can be used without importing any module. They provide basic and essential operations.
</p>

<table border="1" cellpadding="8" cellspacing="0">
<tr>
<th>Function</th>
<th>Definition</th>
<th>Example</th>
</tr>
<tr>
<td>print()</td>
<td>Displays output on the screen</td>
<td><code>print("Hello Python")</code></td>
</tr>
<tr>
<td>len()</td>
<td>Returns the number of items in an object</td>
<td><code>len("Python") → 6</code></td>
</tr>
<tr>
<td>type()</td>
<td>Returns the data type of a variable</td>
<td><code>type(10) → int</code></td>
</tr>
<tr>
<td>range()</td>
<td>Generates a sequence of numbers</td>
<td><code>list(range(1,5)) → [1,2,3,4]</code></td>
</tr>
<tr>
<td>max()</td>
<td>Returns the largest value</td>
<td><code>max(4,9,2) → 9</code></td>
</tr>
<tr>
<td>min()</td>
<td>Returns the smallest value</td>
<td><code>min(4,9,2) → 2</code></td>
</tr>
</table>

<h3>Libraries (Modules)</h3>
<p>
<b>Definition:</b> Libraries (or modules) are collections of pre-written Python code
that extend Python’s functionality. They must be imported before use.
</p>

<pre><code>import math
print(math.sqrt(16))</code></pre>

<pre><code>import random
print(random.randint(1,10))</code></pre>

<pre><code>import os
print(os.getcwd())</code></pre>

<hr>

<h2>4. Sequence and Mapping Data Structures</h2>

<h3>4.1 String (str) – Immutable Sequence of Characters</h3>
<p>
<b>Definition:</b> A string is a sequence of characters enclosed in quotes.
Strings are immutable, meaning their content cannot be changed after creation.
</p>

<pre><code>text = "python"</code></pre>

<h4>String Methods</h4>

<h4>Formatting</h4>
<ul>
<li><b>upper()</b> – Converts to uppercase → <code>"python".upper()</code></li>
<li><b>lower()</b> – Converts to lowercase → <code>"PyThOn".lower()</code></li>
<li><b>capitalize()</b> – Capitalizes first letter → <code>"python".capitalize()</code></li>
<li><b>title()</b> – Capitalizes each word → <code>"hello world".title()</code></li>
</ul>

<h4>Searching</h4>
<ul>
<li><b>find()</b> – Returns index or -1 → <code>"python".find("t")</code></li>
<li><b>index()</b> – Returns index or error → <code>"python".index("p")</code></li>
<li><b>count()</b> – Counts occurrences → <code>"banana".count("a")</code></li>
</ul>

<h4>Checking</h4>
<ul>
<li><b>startswith()</b> → <code>"python".startswith("py")</code></li>
<li><b>endswith()</b> → <code>"python".endswith("on")</code></li>
</ul>

<h4>Validation</h4>
<ul>
<li><b>isalpha()</b> → <code>"Hello".isalpha()</code></li>
<li><b>isdigit()</b> → <code>"123".isdigit()</code></li>
<li><b>isalnum()</b> → <code>"abc123".isalnum()</code></li>
<li><b>isspace()</b> → <code>"   ".isspace()</code></li>
</ul>

<h4>Manipulation</h4>
<ul>
<li><b>strip()</b> → <code>" hi ".strip()</code></li>
<li><b>lstrip()</b> → <code>" hi".lstrip()</code></li>
<li><b>rstrip()</b> → <code>"hi ".rstrip()</code></li>
</ul>

<h4>Splitting & Joining</h4>

<pre><code>"apple,banana,orange".split(",")</code></pre>

<pre><code>"-".join(["2025","01","01"])</code></pre>

<h4>Replacement</h4>

<pre><code>"Hello World".replace("World","Python")</code></pre>

<hr>

<h3>4.2 List (list) – Mutable, Ordered Sequence</h3>

<p>
<b>Definition:</b> A list is an ordered collection of items that is mutable,
meaning elements can be modified.
</p>

<pre><code>numbers = [1, 2, 3]</code></pre>

<h4>Adding Elements</h4>
<ul>
<li><b>append()</b> → <code>[1,2].append(3)</code></li>
<li><b>insert()</b> → <code>[1,3].insert(1,2)</code></li>
<li><b>extend()</b> → <code>[1,2].extend([3,4])</code></li>
</ul>

<h4>Removing Elements</h4>
<ul>
<li><b>remove()</b> → <code>[1,2,3].remove(2)</code></li>
<li><b>pop()</b> → <code>[1,2,3].pop()</code></li>
<li><b>clear()</b> → <code>[1,2].clear()</code></li>
</ul>

<h4>Ordering</h4>
<ul>
<li><b>sort()</b> → <code>[3,1,2].sort()</code></li>
<li><b>reverse()</b> → <code>[1,2,3].reverse()</code></li>
</ul>

<h4>Querying</h4>
<ul>
<li><b>index()</b> → <code>[10,20,30].index(20)</code></li>
<li><b>count()</b> → <code>[1,1,2].count(1)</code></li>
</ul>

<h4>Copying</h4>

<pre><code>list1 = [1,2,3]
list2 = list1.copy()</code></pre>

<h2>4.3 Tuple (<code>tuple</code>)</h2>

<h3>Definition</h3>
<p>
A <strong>tuple</strong> is an <strong>ordered, immutable</strong> collection of elements.
Once created, its values cannot be changed. Tuples are faster than lists and
can be used as <strong>dictionary keys</strong> or <strong>set elements</strong>.
</p>

<h3>Example</h3>
<pre><code>numbers = (10, 20, 30, 20)</code></pre>

<h3>Common Tuple Methods</h3>
<pre><code>numbers.index(20)   # Output: 1
numbers.count(20)   # Output: 2</code></pre>

<h3>Built-in Functions with Tuples</h3>
<pre><code>len(numbers)        # Output: 4
sorted(numbers)     # Output: [10, 20, 20, 30]</code></pre>

<h3>Immutability Example</h3>
<pre><code>numbers[0] = 100    # Error: TypeError</code></pre>

<hr>

<h2>4.4 Set (<code>set</code>)</h2>

<h3>Definition</h3>
<p>
A <strong>set</strong> is a <strong>mutable, unordered</strong> collection of
<strong>unique</strong> elements. It is mainly used for membership testing
and mathematical set operations.
</p>

<h3>Example</h3>
<pre><code>colors = {"red", "blue", "green"}</code></pre>

<h3>Adding &amp; Removing Elements</h3>
<pre><code>colors.add("yellow")
colors.remove("blue")
colors.discard("black")
colors.pop()
colors.clear()</code></pre>

<h3>Set Operations</h3>
<pre><code>A = {1, 2, 3}
B = {3, 4, 5}

A.union(B)
A.intersection(B)
A.difference(B)
A.symmetric_difference(B)</code></pre>

<h3>Set Comparisons</h3>
<pre><code>A.issubset(B)
A.issuperset(B)
A.isdisjoint(B)</code></pre>

<hr>

<h2>4.5 Dictionary (<code>dict</code>)</h2>

<h3>Definition</h3>
<p>
A <strong>dictionary</strong> is a <strong>mutable collection</strong> that stores
data as <strong>key-value pairs</strong>. Keys must be unique and immutable,
while values can be any data type.
</p>

<h3>Example</h3>
<pre><code>student = {
    "name": "Ali",
    "age": 20,
    "course": "Python"
}</code></pre>

<h3>Accessing Dictionary Values</h3>
<pre><code>student["name"]
student.get("age")
student.get("grade", "N/A")</code></pre>

<h3>Dictionary Views</h3>
<pre><code>student.keys()
student.values()
student.items()</code></pre>

<h3>Modifying Dictionary</h3>
<pre><code>student.update({"age": 21})
student.pop("course")
student.setdefault("grade", "A")
student.popitem()</code></pre>

<h3>Creating Dictionary Using <code>fromkeys()</code></h3>
<pre><code>keys = ("a", "b", "c")
dict.fromkeys(keys, 0)</code></pre>

<hr>

<h2>Quick Summary</h2>

<table border="1" cellpadding="8">
  <tr>
    <th>Type</th>
    <th>Ordered</th>
    <th>Mutable</th>
    <th>Unique Elements</th>
  </tr>
  <tr>
    <td>Tuple</td>
    <td>Yes</td>
    <td>No</td>
    <td>No</td>
  </tr>
  <tr>
    <td>Set</td>
    <td>No</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Dictionary</td>
    <td>Yes (keys)</td>
    <td>Yes</td>
    <td>Yes (keys)</td>
  </tr>
</table>

<h2>📌 II. Control Flow and Logic</h2>

<p>
🔁 <strong>Control flow</strong> determines the order in which a program’s instructions
are executed. It helps a program make decisions, repeat tasks, or stop execution.
</p>

<hr>

<h3>🔹 1. Conditional Statements</h3>

<p>
🤔 Conditional statements allow the program to execute different code blocks
based on whether a condition is <strong>True</strong> or <strong>False</strong>.
</p>

<h4>✅ if / elif / else</h4>

<ul>
  <li>🟢 <strong>if</strong> – Executes when the condition is true</li>
  <li>🟡 <strong>elif</strong> – Checks additional conditions</li>
  <li>🔴 <strong>else</strong> – Executes when all conditions are false</li>
</ul>

<pre><code>
age = 18

if age &lt; 18:
    print("You are a minor.")
elif age == 18:
    print("You are exactly 18 years old.")
else:
    print("You are an adult.")
</code></pre>

<h4>⛔ break Statement</h4>

<p>
The <strong>break</strong> statement is used inside loops to immediately terminate
the loop when a specific condition is met.
</p>

<pre><code>
for number in range(1, 6):
    if number == 4:
        break
    print(number)
</code></pre>

<hr>

<h3>🔹 2. Control Statements (Loops)</h3>

<h4>🔄 for Loop</h4>

<p>
A <strong>for loop</strong> is used to iterate over a sequence such as a list, tuple,
string, or range. It is commonly used when the number of iterations is known.
</p>

<pre><code>
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
</code></pre>

<h4>♻️ while Loop</h4>

<p>
A <strong>while loop</strong> executes a block of code as long as a given condition
remains true. It is useful when the number of iterations is not known beforehand.
</p>

<pre><code>
count = 0

while count &lt; 3:
    print(count)
    count += 1
</code></pre>

<hr>

<h2>🧠 III. Functions and Advanced Techniques</h2>

<h3>🔹 1. Defining and Using Functions</h3>

<h4>🛠️ Function (def)</h4>

<p>
A <strong>function</strong> is a reusable block of code designed to perform a
specific task. Functions improve code readability, reduce repetition,
and make programs easier to maintain.
</p>

<pre><code>
def greet(name):
    """This function greets the person passed as a parameter."""
    return f"Hello, {name}!"

print(greet("Alice"))
</code></pre>

<hr>

<p align="center">
✨ <strong>Happy Coding!</strong> ✨<br>
📘 Learn • 💻 Practice • 🚀 Build
</p>





