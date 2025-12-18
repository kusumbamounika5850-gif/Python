<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Python Skills Portfolio</title>
</head>
<body>

    <header>
        <h1>Python Skills Portfolio</h1>
        <p>A summary of practiced skills and theoretical understanding of key Python concepts.</p>
    </header>
    <hr>

    <!-- SECTION I: FUNDAMENTALS -->
    <section id="fundamentals">
        <h2>I. Python Fundamentals</h2>
        
        <h3>1. Core Data Types and Variables</h3>
        <table border="1">
            <thead>
                <tr>
                    <th>Concept</th>
                    <th>Description</th>
                    <th>Key Characteristics</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>Data Types</strong></td>
                    <td>int, float, str, bool</td>
                    <td>Python is dynamically typed; types are checked during execution.</td>
                </tr>
                <tr>
                    <td><strong>Variables</strong></td>
                    <td>Named storage locations using <code>=</code></td>
                    <td>No explicit declaration needed; created upon assignment.</td>
                </tr>
                <tr>
                    <td><strong>Type Conversion</strong></td>
                    <td><code>int()</code>, <code>str()</code>, <code>float()</code></td>
                    <td>Essential for operations requiring specific types (e.g., casting).</td>
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
    </section>

    <!-- SECTION II: DATA STRUCTURES (Collapsible for readability) -->
    <section id="data-structures">
        <h2>II. Sequence & Mapping Data Structures</h2>
        
        <details>
            <summary><strong>4.1 String (str) - Immutable</strong></summary>
            <ul>
                <li><strong>Formatting:</strong> <code>upper()</code>, <code>lower()</code>, <code>title()</code></li>
                <li><strong>Searching:</strong> <code>find()</code>, <code>index()</code>, <code>count()</code></li>
                <li><strong>Validation:</strong> <code>isalpha()</code>, <code>isdigit()</code></li>
            </ul>
        </details>

        <details>
            <summary><strong>4.2 List (list) - Mutable</strong></summary>
            <ul>
                <li><strong>Adding:</strong> <code>append()</code>, <code>insert()</code>, <code>extend()</code></li>
                <li><strong>Removing:</strong> <code>remove()</code>, <code>pop()</code>, <code>clear()</code></li>
                <li><strong>Ordering:</strong> <code>sort()</code>, <code>reverse()</code></li>
            </ul>
        </details>

        <details>
            <summary><strong>4.5 Dictionary (dict) - Mapping</strong></summary>
            <ul>
                <li><strong>Accessing:</strong> <code>get()</code>, <code>keys()</code>, <code>values()</code>, <code>items()</code></li>
                <li><strong>Modification:</strong> <code>update()</code>, <code>popitem()</code>, <code>setdefault()</code></li>
            </ul>
        </details>
    </section>

    <!-- SECTION III: CONTROL FLOW -->
    <section id="control-flow">
        <h2>III. Control Flow and Logic</h2>
        <h3>1. Conditional Statements</h3>
        <p>Uses <code>if</code>, <code>elif</code>, and <code>else</code> for decision making. The <code>break</code> statement terminates loops immediately.</p>
        
        <h3>2. Loops</h3>
        <p><strong>For Loop:</strong> Used for iterating over sequences.</p>
        <pre><code>for item in [1, 2, 3]:
    print(item)</code></pre>
        
        <p><strong>While Loop:</strong> Executes as long as a condition is True.</p>
        <pre><code>while count > 0:
    print(count)
    count -= 1</code></pre>
    </section>

    <!-- SECTION IV: ADVANCED -->
    <section id="advanced">
        <h2>IV. Reusability & Error Handling</h2>
        <ul>
            <li><strong>Functions:</strong> Defined with <code>def</code>; supports positional and keyword arguments.</li>
            <li><strong>Exceptions:</strong> Handled using <code>try</code>, <code>except</code>, <code>finally</code>, and <code>raise</code>.</li>
            <li><strong>File I/O:</strong> Best managed with the <code>with open()</code> context manager.</li>
        </ul>
    </section>

</body>
</html>
