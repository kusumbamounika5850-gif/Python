<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Python Skills Portfolio</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            padding: 25px;
            background-color: #ffffff;
            color: #333;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 3px solid #2c3e50;
            padding-bottom: 5px;
        }
        h2 {
            color: #34495e;
            margin-top: 30px;
        }
        h3 {
            color: #4f5b66;
            margin-top: 20px;
        }
        p {
            margin: 10px 0;
        }
        ul {
            margin-left: 25px;
        }
        li {
            margin-bottom: 6px;
        }
        pre {
            background: #f4f4f4;
            padding: 12px;
            border-left: 4px solid #3498db;
            overflow-x: auto;
        }
        code {
            color: #c7254e;
        }
    </style>
</head>

<body>

<h1>Python Skills Portfolio</h1>

<p>
This portfolio summarizes my practical skills and theoretical understanding
of Python programming concepts, from fundamentals to intermediate-level topics.
</p>

<h2>I. Python Fundamentals</h2>

<h3>1. Core Data Types and Variables</h3>

<p><strong>Data Types:</strong> int, float, str, bool</p>
<p>Python is dynamically typed, meaning data types are checked at runtime.</p>

<p><strong>Variables:</strong> Used to store values and created when assigned.</p>

<p><strong>Type Conversions (Casting):</strong> int(), float(), str(), list(), tuple()</p>

<h3>2. Operators and Expressions</h3>

<ul>
    <li><strong>Arithmetic:</strong> +, -, *, /, %, **, //</li>
    <li><strong>Comparison:</strong> ==, !=, &gt;, &lt;, &gt;=, &lt;=</li>
    <li><strong>Logical:</strong> and, or, not</li>
    <li><strong>Assignment:</strong> =, +=, -=, *=</li>
    <li><strong>Identity:</strong> is, is not</li>
    <li><strong>Membership:</strong> in, not in</li>
</ul>

<h3>3. Built-in Functions and Libraries</h3>

<p>
Common built-in functions include print(), len(), type(), range(), max(), min().
</p>

<p>
Libraries extend Python functionality using the <code>import</code> statement
(e.g., math, random, os).
</p>

<h3>4. Built-in Data Structures</h3>

<h4>4.1 String (str)</h4>
<p>Strings are immutable sequences of characters.</p>

<ul>
    <li>Formatting: upper(), lower(), title()</li>
    <li>Searching: find(), index(), count()</li>
    <li>Validation: isalpha(), isdigit()</li>
    <li>Manipulation: strip(), replace()</li>
</ul>

<h4>4.2 List (list)</h4>
<p>Lists are mutable ordered collections.</p>

<ul>
    <li>append(), insert(), extend()</li>
    <li>remove(), pop(), clear()</li>
    <li>sort(), reverse()</li>
</ul>

<h4>4.3 Tuple (tuple)</h4>
<p>Tuples are immutable and faster than lists.</p>

<ul>
    <li>index(), count()</li>
</ul>

<h4>4.4 Set (set)</h4>
<p>Sets store unique elements and support set operations.</p>

<ul>
    <li>union(), intersection(), difference()</li>
    <li>issubset(), issuperset()</li>
</ul>

<h4>4.5 Dictionary (dict)</h4>
<p>Dictionaries store key-value pairs.</p>

<ul>
    <li>get(), keys(), values(), items()</li>
    <li>update(), pop(), setdefault()</li>
</ul>

<h2>II. Control Flow and Logic</h2>

<h3>1. Conditional Statements</h3>

<p>Python uses if, elif, and else for decision-making.</p>

<h3>2. Loops</h3>

<pre><code>for item in [1, 2, 3]:
    print(item)</code></pre>

<pre><code>count = 0
while count &lt; 5:
    print(count)
    count += 1</code></pre>

<h2>III. Functions and Advanced Techniques</h2>

<h3>1. Functions</h3>

<pre><code>def greet(name):
    return f"Hello, {name}!"</code></pre>

<h3>Recursion Example</h3>

<pre><code>def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)</code></pre>

<h3>2. Functional Programming</h3>

<ul>
    <li>Lambda functions</li>
    <li>map()</li>
    <li>filter()</li>
    <li>reduce()</li>
</ul>

<h3>3. Comprehensions</h3>

<pre><code>squares = [x**2 for x in range(10)]
even_squares = [x**2 for x in range(10) if x % 2 == 0]</code></pre>

<pre><code>names = ['Alice', 'Bob', 'Charlie']
name_lengths = {name: len(name) for name in names}</code></pre>

</body>
</html>
