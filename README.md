<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Python Skills Portfolio: From Fundamentals to Intermediate Concepts</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.7;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

        header p {
            font-size: 1.1em;
            opacity: 0.95;
        }

        main {
            padding: 40px;
        }

        h2 {
            color: #667eea;
            font-size: 2em;
            margin-top: 40px;
            margin-bottom: 20px;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
        }

        h3 {
            color: #764ba2;
            font-size: 1.5em;
            margin-top: 30px;
            margin-bottom: 15px;
        }

        h4 {
            color: #555;
            font-size: 1.2em;
            margin-top: 20px;
            margin-bottom: 12px;
        }

        p {
            margin-bottom: 15px;
            text-align: justify;
        }

        ul, ol {
            margin-left: 30px;
            margin-bottom: 15px;
        }

        li {
            margin-bottom: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            background: #f9f9f9;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        th {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px;
            text-align: left;
            font-weight: 600;
        }

        td {
            padding: 12px 15px;
            border-bottom: 1px solid #ddd;
        }

        tr:hover {
            background: #f0f0f0;
        }

        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            color: #d63384;
        }

        pre {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            margin: 15px 0;
            font-family: 'Courier New', monospace;
            line-height: 1.5;
        }

        pre code {
            background: none;
            color: inherit;
            padding: 0;
        }

        .section-divider {
            border-top: 2px solid #667eea;
            margin: 40px 0;
        }

        .highlight {
            background: #fff3cd;
            padding: 15px;
            border-left: 4px solid #ffc107;
            margin: 15px 0;
            border-radius: 4px;
        }

        .math {
            display: inline-block;
            font-style: italic;
            color: #764ba2;
        }

        footer {
            background: #f5f5f5;
            padding: 20px;
            text-align: center;
            color: #666;
            border-top: 1px solid #ddd;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.8em;
            }

            h2 {
                font-size: 1.5em;
            }

            h3 {
                font-size: 1.2em;
            }

            table {
                font-size: 0.9em;
            }

            th, td {
                padding: 10px;
            }

            main {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Python Skills Portfolio</h1>
            <p>From Fundamentals to Intermediate Concepts</p>
        </header>

        <main>
            <p><strong>Overview:</strong> This document summarizes my practiced skills and theoretical understanding of key Python programming concepts, structured for easy reference and review.</p>

            <div class="section-divider"></div>

            <!-- Section I: Python Fundamentals -->
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
                        <td><strong>Data Types</strong></td>
                        <td>The classification of data items. Practiced types include <code>int</code> (integers), <code>float</code> (floating-point numbers), <code>str</code> (strings), and <code>bool</code> (Boolean values: <code>True</code>/<code>False</code>).</td>
                        <td>Python is dynamically typed, meaning the type is checked during execution.</td>
                    </tr>
                    <tr>
                        <td><strong>Variables</strong></td>
                        <td>Named storage locations used to hold values. Assignment is done using the <code>=</code> operator.</td>
                        <td>Variables do not need explicit declaration; they are created when a value is assigned.</td>
                    </tr>
                    <tr>
                        <td><strong>Type Conversions (Casting)</strong></td>
                        <td>Explicitly changing a variable's data type using built-in functions like <code>int()</code>, <code>str()</code>, <code>float()</code>, <code>list()</code>, and <code>tuple()</code>.</td>
                        <td>Essential for operations that require specific data types (e.g., concatenating a number with a string).</td>
                    </tr>
                </tbody>
            </table>

            <h3>2. Operators and Expressions</h3>

            <p>Operators are special symbols that perform operations on variables and values.</p>

            <ul>
                <li><strong>Arithmetic Operators:</strong> <code>+</code>, <code>-</code>, <code>*</code>, <code>/</code>, <code>%</code> (modulus), <code>**</code> (exponentiation), <code>//</code> (floor division).</li>
                <li><strong>Comparison Operators:</strong> Used to compare values and return a Boolean result: <code>==</code>, <code>!=</code>, <code>&gt;</code>, <code>&lt;</code>, <code>&gt;=</code>, <code>&lt;=</code>.</li>
                <li><strong>Logical Operators:</strong> Used to combine conditional statements: <code>and</code>, <code>or</code>, <code>not</code>.</li>
                <li><strong>Assignment Operators:</strong> Used to assign values to variables: <code>=</code>, <code>+=</code>, <code>-=</code>, <code>*=</code>, etc.</li>
                <li><strong>Identity Operators:</strong> Used to compare the memory locations of two objects: <code>is</code>, <code>is not</code>.</li>
                <li><strong>Membership Operators:</strong> Used to test if a sequence contains a specific value: <code>in</code>, <code>not in</code>.</li>
            </ul>

            <h3>3. Built-in Functions and Libraries</h3>

            <ul>
                <li><strong>Built-in Functions:</strong> Functions that are always available for use, such as <code>print()</code>, <code>len()</code>, <code>type()</code>, <code>range()</code>, <code>max()</code>, and <code>min()</code>. These provide core functionality without needing imports.</li>
                <li><strong>Libraries (Modules):</strong> Collections of pre-written code that can be imported to extend Python's capabilities (e.g., <code>math</code>, <code>random</code>, <code>os</code>). The <code>import</code> statement is used to access them.</li>
            </ul>

            <h3>4. Sequence and Mapping Data Structures: Detailed Built-in Functions</h3>

            <p>Python's core data structures are powerful and come equipped with a rich set of built-in methods (functions) that allow for efficient manipulation and querying of data. Understanding these methods is key to writing idiomatic and high-performance Python code.</p>

            <h4>4.1. String (<code>str</code>) - Immutable Sequence of Characters</h4>

            <p>Strings are immutable, meaning their content cannot be changed after creation. All methods return a new string.</p>

            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Method</th>
                        <th>Description & Example</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Formatting</strong></td>
                        <td><code>upper()</code>, <code>lower()</code>, <code>capitalize()</code>, <code>title()</code></td>
                        <td>Change case. <code>title()</code> capitalizes the first letter of every word.</td>
                    </tr>
                    <tr>
                        <td><strong>Searching</strong></td>
                        <td><code>find(sub)</code>, <code>index(sub)</code>, <code>count(sub)</code></td>
                        <td><code>find()</code> returns the lowest index of the substring (or -1 if not found). <code>index()</code> is similar but raises a <code>ValueError</code> if not found. <code>count()</code> returns the number of non-overlapping occurrences.</td>
                    </tr>
                    <tr>
                        <td><strong>Checking</strong></td>
                        <td><code>startswith(prefix)</code>, <code>endswith(suffix)</code></td>
                        <td>Check if the string begins or ends with a specified substring.</td>
                    </tr>
                    <tr>
                        <td><strong>Validation</strong></td>
                        <td><code>isalpha()</code>, <code>isdigit()</code>, <code>isalnum()</code>, <code>isspace()</code></td>
                        <td>Check if all characters in the string are alphabetic, digits, alphanumeric, or whitespace, respectively.</td>
                    </tr>
                    <tr>
                        <td><strong>Manipulation</strong></td>
                        <td><code>strip()</code>, <code>lstrip()</code>, <code>rstrip()</code></td>
                        <td>Remove leading and trailing whitespace (or specified characters).</td>
                    </tr>
                    <tr>
                        <td><strong>Splitting/Joining</strong></td>
                        <td><code>split(sep)</code>, <code>join(iterable)</code></td>
                        <td><code>split()</code> divides the string into a list of substrings based on a delimiter (<code>sep</code>). <code>join()</code> concatenates an iterable of strings using the string itself as the separator.</td>
                    </tr>
                    <tr>
                        <td><strong>Replacement</strong></td>
                        <td><code>replace(old, new)</code></td>
                        <td>Returns a copy of the string with all occurrences of <code>old</code> substring replaced by <code>new</code>.</td>
                    </tr>
                </tbody>
            </table>

            <h4>4.2. List (<code>list</code>) - Mutable, Ordered Sequence</h4>

            <p>Lists are mutable, allowing for in-place modification, which makes them highly flexible for dynamic data collections.</p>

            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Method</th>
                        <th>Description & Example</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Adding Elements</strong></td>
                        <td><code>append(item)</code>, <code>insert(index, item)</code>, <code>extend(iterable)</code></td>
                        <td><code>append()</code> adds a single item to the end. <code>insert()</code> adds an item at a specific index. <code>extend()</code> adds all items from an iterable to the end of the list.</td>
                    </tr>
                    <tr>
                        <td><strong>Removing Elements</strong></td>
                        <td><code>remove(item)</code>, <code>pop(index)</code>, <code>clear()</code></td>
                        <td><code>remove()</code> deletes the first occurrence of a specified value. <code>pop()</code> removes and returns the item at a given index (defaults to the last item). <code>clear()</code> removes all items.</td>
                    </tr>
                    <tr>
                        <td><strong>Ordering</strong></td>
                        <td><code>sort()</code>, <code>reverse()</code></td>
                        <td><code>sort()</code> sorts the list in-place (modifies the original list). <code>reverse()</code> reverses the elements of the list in-place.</td>
                    </tr>
                    <tr>
                        <td><strong>Querying</strong></td>
                        <td><code>index(item)</code>, <code>count(item)</code></td>
                        <td><code>index()</code> returns the index of the first occurrence of the item. <code>count()</code> returns the number of times the item appears.</td>
                    </tr>
                    <tr>
                        <td><strong>Copying</strong></td>
                        <td><code>copy()</code></td>
                        <td>Returns a shallow copy of the list.</td>
                    </tr>
                </tbody>
            </table>

            <h4>4.3. Tuple (<code>tuple</code>) - Immutable, Ordered Sequence</h4>

            <p>Tuples are immutable, making them faster than lists and suitable for use as dictionary keys or elements in a set. Their primary methods are limited due to their immutability.</p>

            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Method</th>
                        <th>Description & Example</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Querying</strong></td>
                        <td><code>index(item)</code>, <code>count(item)</code></td>
                        <td>These are the two main methods. <code>index()</code> finds the first occurrence of a value, and <code>count()</code> returns the number of times a value appears.</td>
                    </tr>
                    <tr>
                        <td><strong>Built-in Functions</strong></td>
                        <td><code>len(tuple)</code>, <code>sorted(tuple)</code></td>
                        <td>While not methods, built-in functions like <code>len()</code> (size) and <code>sorted()</code> (returns a new sorted <em>list</em>) are commonly used with tuples.</td>
                    </tr>
                </tbody>
            </table>

            <h4>4.4. Set (<code>set</code>) - Mutable, Unordered Collection of Unique Items</h4>

            <p>Sets are optimized for membership testing and mathematical set operations. They only store unique, hashable elements.</p>

            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Method</th>
                        <th>Description & Example</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Adding/Removing</strong></td>
                        <td><code>add(item)</code>, <code>remove(item)</code>, <code>discard(item)</code>, <code>pop()</code>, <code>clear()</code></td>
                        <td><code>add()</code> adds a single element. <code>remove()</code> removes an element (raises <code>KeyError</code> if not found). <code>discard()</code> removes an element if present (no error if not found). <code>pop()</code> removes and returns an arbitrary element.</td>
                    </tr>
                    <tr>
                        <td><strong>Set Operations</strong></td>
                        <td><code>union()</code>, <code>intersection()</code>, <code>difference()</code>, <code>symmetric_difference()</code></td>
                        <td>Perform standard set algebra: combining two sets, finding common elements, finding elements only in the first set, and finding elements in either set but not both, respectively.</td>
                    </tr>
                    <tr>
                        <td><strong>Comparison</strong></td>
                        <td><code>issubset()</code>, <code>issuperset()</code>, <code>isdisjoint()</code></td>
                        <td>Check relationships between two sets (e.g., if one set is entirely contained within another).</td>
                    </tr>
                </tbody>
            </table>

            <h4>4.5. Dictionary (<code>dict</code>) - Mutable Mapping of Key-Value Pairs</h4>

            <p>Dictionaries map unique, immutable keys to values. They are highly efficient for data retrieval.</p>

            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Method</th>
                        <th>Description & Example</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Accessing</strong></td>
                        <td><code>get(key, default)</code>, <code>keys()</code>, <code>values()</code>, <code>items()</code></td>
                        <td><code>get()</code> safely retrieves a value by key, returning a default value (or <code>None</code>) if the key is not found, avoiding a <code>KeyError</code>. <code>keys()</code>, <code>values()</code>, and <code>items()</code> return view objects of the dictionary's keys, values, and key-value pairs, respectively.</td>
                    </tr>
                    <tr>
                        <td><strong>Modification</strong></td>
                        <td><code>update(other_dict)</code>, <code>pop(key)</code>, <code>popitem()</code>, <code>setdefault(key, default)</code></td>
                        <td><code>update()</code> merges another dictionary or iterable of key-value pairs into the current dictionary. <code>pop()</code> removes a key and returns its value. <code>popitem()</code> removes and returns an arbitrary (last inserted) key-value pair. <code>setdefault()</code> returns the value of the key, but if the key is not found, it inserts the key with the default value.</td>
                    </tr>
                    <tr>
                        <td><strong>Creation</strong></td>
                        <td><code>fromkeys(iterable, value)</code></td>
                        <td>A class method that creates a new dictionary with keys from an iterable and values set to a specified value (defaults to <code>None</code>).</td>
                    </tr>
                </tbody>
            </table>

            <div class="section-divider"></div>

            <!-- Section II: Control Flow and Logic -->
            <h2>II. Control Flow and Logic</h2>

            <p>Control flow statements dictate the order in which the program's code executes.</p>

            <h3>1. Conditional Statements</h3>

            <p>Conditional statements allow the program to make decisions and execute different code blocks based on whether a condition is <code>True</code> or <code>False</code>.</p>

            <ul>
                <li><strong><code>if</code> / <code>elif</code> / <code>else</code>:</strong> The core structure for decision-making. Code under <code>if</code> executes if the condition is true; <code>elif</code> (else if) checks subsequent conditions; and <code>else</code> executes if all preceding conditions are false.</li>
                <li><strong><code>break</code>:</strong> A flow control statement used exclusively inside loops (<code>for</code> or <code>while</code>). When encountered, it immediately terminates the current loop, and program execution resumes at the statement immediately following the loop.</li>
            </ul>

            <h3>2. Control Statements (Loops)</h3>

            <p>Loops are used to execute a block of code repeatedly.</p>

            <ul>
                <li><strong><code>for</code> Loop:</strong> Used for iteration over a sequence (like a list, tuple, dictionary, set, or string) or other iterable objects. It is typically used when the number of iterations is known.
                    <pre><code># Example: Iterating through a list
for item in [1, 2, 3]:
    print(item)</code></pre>
                </li>
                <li><strong><code>while</code> Loop:</strong> Executes a block of code as long as a specified condition is true. It is typically used when the number of iterations is not known beforehand and depends on a condition being met.
                    <pre><code># Example: Loop until a condition is false
count = 0
while count < 5:
    print(count)
    count += 1</code></pre>
                </li>
            </ul>

            <div class="section-divider"></div>

            <!-- Section III: Functions and Advanced Techniques -->
            <h2>III. Functions and Advanced Techniques</h2>

            <h3>1. Defining and Using Functions</h3>

            <ul>
                <li><strong><code>def</code> Function:</strong> The standard way to define a reusable block of code. Functions promote modularity, code reuse, and readability.
                    <pre><code>def greet(name):
    """This function greets the person passed in as a parameter."""
    return f"Hello, {name}!"</code></pre>
                </li>
            </ul>

            <h4>Recursion: Solving Problems by Self-Reference</h4>

            <p>Recursion is a powerful programming technique where a function calls itself one or more times to solve a problem. It is fundamentally about breaking down a complex problem into smaller, more manageable subproblems that are identical in nature to the original problem.</p>

            <h5 style="color: #555; font-size: 1.1em; margin-top: 15px; margin-bottom: 10px;"><strong>Key Components of Recursion:</strong></h5>

            <ol>
                <li><strong>Base Case:</strong> This is the condition that stops the recursion. Without a base case, the function would call itself infinitely, leading to a <strong>Stack Overflow Error</strong>. The base case solves the simplest version of the problem directly.</li>
                <li><strong>Recursive Step:</strong> This is where the function calls itself, but with a modified input that moves the function closer to the base case.</li>
            </ol>

            <h5 style="color: #555; font-size: 1.1em; margin-top: 15px; margin-bottom: 10px;"><strong>Example: Calculating Factorial</strong></h5>

            <p>The factorial of a non-negative integer <span class="math">n</span> (denoted <span class="math">n!</span>) is the product of all positive integers less than or equal to <span class="math">n</span>. The recursive definition is:</p>

            <p style="text-align: center; font-style: italic; color: #764ba2; margin: 15px 0;">n! = n × (n-1)!</p>

            <p>with the base case being <span class="math">0! = 1</span>.</p>

            <pre><code>def factorial(n):
    # 1. Base Case: Stops the recursion
    if n == 0:
        return 1
    # 2. Recursive Step: Calls itself with a smaller input (n-1)
    else:
        return n * factorial(n - 1)

# Example Usage:
# factorial(4) -> 4 * factorial(3)
# -> 4 * (3 * factorial(2))
# -> 4 * (3 * (2 * factorial(1)))
# -> 4 * (3 * (2 * (1 * factorial(0))))
# -> 4 * (3 * (2 * (1 * 1)))
# -> 24</code></pre>

            <h5 style="color: #555; font-size: 1.1em; margin-top: 15px; margin-bottom: 10px;"><strong>Advantages and Disadvantages:</strong></h5>

            <table>
                <thead>
                    <tr>
                        <th>Aspect</th>
                        <th>Advantage</th>
                        <th>Disadvantage</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Readability</strong></td>
                        <td>Often leads to cleaner, more intuitive code for problems naturally defined recursively (e.g., tree traversals, mathematical sequences).</td>
                        <td></td>
                    </tr>
                    <tr>
                        <td><strong>Complexity</strong></td>
                        <td></td>
                        <td>Can be harder to trace and debug than iterative solutions.</td>
                    </tr>
                    <tr>
                        <td><strong>Performance</strong></td>
                        <td></td>
                        <td>Each recursive call adds a new stack frame, consuming more memory and potentially leading to slower execution than an equivalent iterative loop.</td>
                    </tr>
                </tbody>
            </table>

            <h3>2. Functional Programming Concepts</h3>

            <p>These concepts allow for writing more concise and expressive code, often dealing with iterables.</p>

            <ul>
                <li><strong>Lambda Functions:</strong> Small, anonymous functions defined using the <code>lambda</code> keyword. They can take any number of arguments but can only have one expression. They are often used as arguments to higher-order functions like <code>map</code> and <code>filter</code>.
                    <pre><code># Example: A lambda function to square a number
square = lambda x: x * x</code></pre>
                </li>
                <li><strong><code>map</code>:</strong> Applies a given function to every item of an iterable (like a list) and returns a <code>map</code> object (which is an iterator). It is used for transforming data.</li>
                <li><strong><code>filter</code>:</strong> Constructs an iterator from elements of an iterable for which a function returns <code>True</code>. It is used for selecting a subset of data.</li>
                <li><strong><code>reduce</code>:</strong> (Found in the <code>functools</code> module) Applies a function cumulatively to the items of an iterable, reducing the iterable to a single value. It is used for aggregation.</li>
            </ul>

            <h3>3. Comprehensions</h3>

            <p>Comprehensions provide a concise, readable, and efficient way to create data structures. They are generally preferred over traditional <code>for</code> loops for simple creation tasks.</p>

            <ul>
                <li><strong>List Comprehensions:</strong> A single line of code to create a list based on an existing iterable. They can include conditional logic (<code>if</code> clauses).
                    <pre><code># Example: Creating a list of squares
squares = [x**2 for x in range(10)]
# Example with condition:
even_squares = [x**2 for x in range(10) if x % 2 == 0]</code></pre>
                </li>
                <li><strong>Dictionary Comprehensions:</strong> Used to create dictionaries quickly, often by iterating over a sequence and creating key-value pairs.
                    <pre><code># Example: Creating a dictionary from a list
names = ['Alice', 'Bob', 'Charlie']
name_lengths = {name: len(name) for name in names}
# Result: {'Alice': 5, 'Bob': 3, 'Charlie': 7}</code></pre>
                </li>
            </ul>

        </main>

        <footer>
            <p>&copy; 2025 Python Skills Portfolio. All rights reserved.</p>
            <p>Created for educational and reference purposes.</p>
        </footer>
    </div>
</body>
</html>
