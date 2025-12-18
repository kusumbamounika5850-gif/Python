<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Python Skills Portfolio</title>
    <style>
        body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; line-height: 1.6; color: #333; max-width: 900px; margin: 0 auto; padding: 20px; }
        h1 { color: #2c3e50; border-bottom: 2px solid #3498db; padding-bottom: 10px; }
        h2 { color: #2980b9; margin-top: 30px; border-left: 5px solid #3498db; padding-left: 10px; }
        h3 { color: #16a085; margin-top: 20px; }
        table { border-collapse: collapse; width: 100%; margin: 20px 0; background-color: #fff; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #f2f2f2; font-weight: bold; }
        tr:nth-child(even) { background-color: #f9f9f9; }
        code { background-color: #f4f4f4; padding: 2px 5px; border-radius: 4px; font-family: "Courier New", Courier, monospace; color: #d63384; }
        pre { background-color: #2d3436; color: #dfe6e9; padding: 15px; border-radius: 5px; overflow-x: auto; font-family: "Courier New", Courier, monospace; }
        .keyword { color: #fab1a0; }
        .comment { color: #636e72; }
    </style>
</head>
<body>

    <h1>Python Skills Portfolio</h1>
    <p>This document summarizes practiced skills and theoretical understanding of key Python programming concepts as of 2025.</p>

    <h2>I. Python Fundamentals</h2>
    
    <h3>1. Core Data Types and Variables</h3>
    <table>
        <thead>
            <tr>
                <th>Concept</th>
                <th>Description</th>
                <th>Key Characteristics</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Data Types</td>
                <td>Classification of items (<code>int</code>, <code>float</code>, <code>str</code>, <code>bool</code>).</td>
                <td>Python is dynamically typed (checked during execution).</td>
            </tr>
            <tr>
                <td>Variables</td>
                <td>Named storage locations using <code>=</code> operator.</td>
                <td>No explicit declaration needed; created upon assignment.</td>
            </tr>
            <tr>
                <td>Casting</td>
                <td>Explicitly changing types using <code>int()</code>, <code>str()</code>, etc.</td>
                <td>Essential for type-specific operations like concatenation.</td>
            </tr>
        </tbody>
    </table>

    <h3>2. Operators and Expressions</h3>
    <ul>
        <li><strong>Arithmetic:</strong> <code>+</code>, <code>-</code>, <code>*</code>, <code>/</code>, <code>%</code>, <code>**</code>, <code>//</code></li>
        <li><strong>Comparison:</strong> <code>==</code>, <code>!=</code>, <code>&gt;</code>, <code>&lt;</code>, <code>&gt;=</code>, <code>&lt;=</code></li>
        <li><strong>Logical:</strong> <code>and</code>, <code>or</code>, <code>not</code></li>
        <li><strong>Identity/Membership:</strong> <code>is</code>, <code>is not</code>, <code>in</code>, <code>not in</code></li>
    </ul>

    <h3>3. Data Structure Methods (Highlights)</h3>
    <h4>List (Mutable)</h4>
    <table>
        <thead>
            <tr>
                <th>Category</th>
                <th>Method</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Adding</td>
                <td><code>append()</code>, <code>insert()</code>, <code>extend()</code></td>
                <td>Adding single items or iterables to a list.</td>
            </tr>
            <tr>
                <td>Removing</td>
                <td><code>remove()</code>, <code>pop()</code>, <code>clear()</code></td>
                <td>Deleting items by value or index.</td>
            </tr>
        </tbody>
    </table>

    <h2>II. Control Flow and Logic</h2>
    
    <h3>1. Conditional Statements</h3>
    <p><code>if / elif / else</code> structures allow decision-making based on Boolean conditions.</p>

    <h3>2. Loops</h3>
    <p><strong>for Loop:</strong> Used for iterating over a sequence.</p>
    <pre><code><span class="keyword">for</span> item <span class="keyword">in</span> [<span class="keyword">1, 2, 3</span>]:
    <span class="keyword">print</span>(item)</code></pre>

    <p><strong>while Loop:</strong> Executes as long as a condition is <code>True</code>.</p>
    <pre><code>count = 0
<span class="keyword">while</span> count < 3:
    <span class="keyword">print</span>(<span class="keyword">f</span>"Count is {count}")
    count += 1</code></pre>

    <h2>III. Functions and Modularity</h2>
    <ul>
        <li><strong>Definition:</strong> Created using the <code>def</code> keyword.</li>
        <li><strong>Return Statement:</strong> Exits a function and passes back data to the caller.</li>
        <li><strong>Scope:</strong> Distinction between <strong>Local</strong> (inside function) and <strong>Global</strong> (module-level) variables.</li>
    </ul>

    <h2>IV. Error and Exception Handling</h2>
    <p>Robust code uses <code>try</code>, <code>except</code>, <code>finally</code>, and <code>raise</code> to manage runtime errors without crashing the application.</p>

    <hr>
    <p><em>For further reference, visit the <a href="docs.python.org">Official Python Documentation</a>.</em></p>

</body>
</html>
