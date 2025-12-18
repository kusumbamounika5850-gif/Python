<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Python Fundamentals</title>

<style>
    body {
        font-family: "Segoe UI", Arial, sans-serif;
        background: #f4f6f9;
        margin: 0;
        padding: 20px;
        line-height: 1.6;
    }

    h1, h2, h3, h4 {
        color: #2c3e50;
    }

    h1 {
        text-align: center;
        background: #2c3e50;
        color: white;
        padding: 15px;
        border-radius: 8px;
    }

    h2 {
        margin-top: 30px;
        padding: 10px;
        background: #ecf0f1;
        border-left: 6px solid #3498db;
        border-radius: 4px;
    }

    h3 {
        margin-top: 20px;
        color: #2980b9;
    }

    h4 {
        color: #34495e;
    }

    .card {
        background: white;
        border: 1px solid #dcdcdc;
        border-radius: 8px;
        padding: 20px;
        margin: 20px 0;
        box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    pre {
        background: #1e1e1e;
        color: #dcdcdc;
        padding: 15px;
        border-radius: 6px;
        overflow-x: auto;
    }

    code {
        color: #e67e22;
        font-weight: bold;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        margin: 15px 0;
        background: white;
    }

    th {
        background: #3498db;
        color: white;
        padding: 10px;
    }

    td {
        padding: 8px;
        border: 1px solid #ccc;
        text-align: center;
    }

    ul li {
        margin: 6px 0;
    }

    .icon {
        font-size: 1.2em;
        margin-right: 6px;
    }

    .note {
        background: #eaf6ff;
        border-left: 5px solid #3498db;
        padding: 10px;
        margin: 15px 0;
        border-radius: 4px;
    }

    hr {
        border: none;
        height: 1px;
        background: #ccc;
        margin: 30px 0;
    }
</style>
</head>

<body>

<h1>🐍 Python Programming Guide</h1>

<div class="card">
<h2>📘 I. Python Fundamentals</h2>

<h3>🔹 Variables</h3>
<p><strong>Variable</strong> stores a value in memory. Python detects the data type automatically.</p>

<pre><code>
x = 10
name = "Alice"
</code></pre>

<h3>📦 Core Data Types</h3>

<table>
<tr><th>Type</th><th>Description</th><th>Example</th></tr>
<tr><td>int</td><td>Whole numbers</td><td>10</td></tr>
<tr><td>float</td><td>Decimal numbers</td><td>3.14</td></tr>
<tr><td>str</td><td>Text</td><td>"Hello"</td></tr>
<tr><td>bool</td><td>True / False</td><td>True</td></tr>
<tr><td>list</td><td>Mutable sequence</td><td>[1,2,3]</td></tr>
<tr><td>tuple</td><td>Immutable sequence</td><td>(1,2)</td></tr>
<tr><td>set</td><td>Unique values</td><td>{1,2}</td></tr>
<tr><td>dict</td><td>Key-value pairs</td><td>{"a":1}</td></tr>
</table>
</div>

<div class="card">
<h2>⚙️ II. Operators & Expressions</h2>

<h3>➕ Arithmetic Operators</h3>

<pre><code>
a = 10
b = 3
print(a + b)
print(a ** b)
</code></pre>

<h3>🔍 Comparison Operators</h3>
<pre><code>
x = 5
y = 10
print(x < y)
</code></pre>

<h3>🔗 Logical Operators</h3>
<pre><code>
print(a > 3 and b > 2)
</code></pre>
</div>

<div class="card">
<h2>📚 III. Built-in Functions & Libraries</h2>

<h3>🧰 Built-in Functions</h3>
<ul>
<li>🖨️ <code>print()</code></li>
<li>📏 <code>len()</code></li>
<li>🔎 <code>type()</code></li>
</ul>

<h3>📦 Modules</h3>
<pre><code>
import math
print(math.sqrt(16))
</code></pre>
</div>

<div class="card">
<h2>🧠 IV. Control Flow</h2>

<h3>❓ Conditional Statements</h3>
<pre><code>
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
</code></pre>

<h3>🔄 Loops</h3>
<pre><code>
for i in range(3):
    print(i)
</code></pre>
</div>

<div class="card">
<h2>🛠️ V. Functions</h2>
<pre><code>
def greet(name):
    return "Hello " + name
</code></pre>
</div>

<div class="note">
✅ <strong>Tip:</strong> This layout is ideal for notes, tutorials, or PDFs.
</div>

</body>
</html>
