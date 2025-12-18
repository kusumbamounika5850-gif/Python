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



