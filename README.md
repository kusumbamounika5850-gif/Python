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

<h2>Summary</h2>
<ul>
  <li>Variables store data</li>
  <li>Data types define the type of data</li>
  <li>Operators perform operations</li>
  <li>Expressions combine values and operators</li>
</ul>
