<h1 align="center">🐍 Python Learning Roadmap</h1>

<p align="center">
  <i>This README explains Python concepts learned from Basics to Intermediate level in a clear and beginner-friendly way.</i>
</p>

<hr>

<h2>📘 Python Basics</h2>

<h3>1. Data Types</h3>
<p>
A data type tells Python <b>what kind of data</b> a value represents and <b>what operations</b> can be performed on it.
Python is a dynamically typed language, which means the data type is decided automatically at runtime based on the value assigned.
</p>

<p>
Common built-in data types include:
</p>
<ul>
  <li><b>int</b> – whole numbers</li>
  <li><b>float</b> – decimal numbers</li>
  <li><b>str</b> – text data</li>
  <li><b>list</b> – ordered, mutable collection</li>
  <li><b>tuple</b> – ordered, immutable collection</li>
  <li><b>set</b> – unordered collection of unique values</li>
  <li><b>dict</b> – key–value pairs</li>
</ul>

<pre><code>x = 10        # int
price = 99.5  # float
name = "Ram"  # string
</code></pre>

<hr>

<h3>2. Variables</h3>
<p>
Variables are names that <b>reference values stored in memory</b>.
In Python, variables do not require explicit type declaration.
The variable automatically points to the object created in memory.
</p>

<p>
A variable can store:
</p>
<ul>
  <li>A number</li>
  <li>A string</li>
  <li>The result of an expression</li>
</ul>

<pre><code>a = 5
b = "Python"
c = a + 10
</code></pre>

<hr>

<h3>3. Print Methods</h3>
<p>
The <b>print()</b> function is used to display output to the console.
Python provides multiple ways to format output depending on the need.
</p>

<ul>
  <li>Using commas – adds space automatically</li>
  <li>Using + operator – concatenates strings</li>
  <li>Using format identifiers (%)</li>
  <li>Using f-strings – modern and readable</li>
</ul>

<pre><code>print("Hello", "World")
print("Hello" + " World")
print("Age is %d" % 25)
print(f"Score is {90}")
</code></pre>

<hr>

<h3>4. Type Conversions</h3>
<p>
Type conversion is the process of converting one data type into another.
This is commonly required when taking input from users or performing calculations.
</p>

<p>
Python supports both implicit and explicit type conversion.
</p>

<pre><code>int(3.7)        # float to int
float(10)       # int to float
str(100)        # int to string
int("25")       # string to int
float("3.14")   # string to float
</code></pre>

<hr>

<h3>5. Operators in Python</h3>
<p>
Operators are special symbols used to perform operations on variables and values.
</p>

<ul>
  <li><b>Arithmetic Operators</b>: +, -, *, /, %, //</li>
  <li><b>Assignment Operators</b>: =, +=, -=, *=</li>
  <li><b>Comparison Operators</b>: ==, !=, >, <, >=, <=</li>
  <li><b>Logical Operators</b>: and, or, not</li>
  <li><b>Membership Operators</b>: in, not in</li>
  <li><b>Identity Operators</b>: is, is not</li>
  <li><b>Bitwise Operators</b>: &, |, ^, <<, >></li>
</ul>

<pre><code>a = 10
b = 5
a > b
a += 2
"x" in "text"
</code></pre>

<hr>

<h3>6. Strings</h3>
<p>
Strings are sequences of characters enclosed in quotes.
Strings are <b>immutable</b>, meaning once created, they cannot be changed.
</p>

<p>
Strings support indexing, slicing, and skipping.
</p>

<pre><code>s = "Python"
s[0]       # indexing
s[1:4]     # slicing
s[::2]     # skipping
</code></pre>

<hr>

<h3>7. Lists</h3>
<p>
Lists are ordered collections that can store multiple values.
Lists are <b>mutable</b>, so elements can be added, removed, or modified.
</p>

<pre><code>lst = [1, 2, 3]
lst.append(4)
lst[0] = 10
</code></pre>

<hr>

<h3>8. Tuples</h3>
<p>
Tuples are similar to lists but are <b>immutable</b>.
They are used when data should not be modified.
</p>

<pre><code>t = (1, 2, 3)
t[1]
</code></pre>

<hr>

<h3>9. Sets</h3>
<p>
Sets are unordered collections that store only unique values.
They do not support indexing or slicing.
Sets use hashing internally.
</p>

<pre><code>s = {1, 2, 3, 3}
# Result: {1, 2, 3}
</code></pre>

<hr>

<h3>10. Dictionary</h3>
<p>
Dictionaries store data as key–value pairs.
They are mutable and use hashing for fast access.
</p>

<pre><code>d = {"name": "Ram", "age": 25}
d["name"]
</code></pre>

<hr>

<h2>📗 Intermediate Python</h2>

<h3>1. Control Statements</h3>

<h4>For Loop</h4>
<p>
For loops iterate over sequences like strings, lists, tuples, sets, and dictionaries.
</p>

<pre><code>for i in range(5):
    print(i)
</code></pre>

<h4>While Loop</h4>
<p>
While loops continue execution as long as a condition remains true.
</p>

<pre><code>n = 1
while n <= 5:
    print(n)
    n += 1
</code></pre>

<h4>Break Statement</h4>
<p>
The break statement stops loop execution immediately.
</p>

<pre><code>for i in range(10):
    if i == 5:
        break
    print(i)
</code></pre>

<hr>

<h3>2. Conditional Statements</h3>
<p>
Conditional statements allow programs to make decisions.
</p>

<pre><code>if a > b:
    print("A is greater")
elif a == b:
    print("Equal")
else:
    print("B is greater")
</code></pre>

<hr>

<h3>3. Functions</h3>
<p>
Functions are reusable blocks of code that perform a specific task.
They help in modularizing programs and avoiding repetition.
</p>

<pre><code>def add(a, b):
    return a + b
</code></pre>

<pre><code>square = lambda x: x * x
list(map(square, [1, 2, 3]))
</code></pre>

<hr>

<h3>4. Comprehensions</h3>
<p>
Comprehensions provide a concise way to create collections using a single line.
</p>

<pre><code>squares = [x*x for x in range(5)]
data = {x: x*x for x in range(3)}
</code></pre>

