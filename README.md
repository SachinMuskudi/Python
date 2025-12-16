<h1 align="center">🐍 Python Learning Roadmap</h1>

<p align="center">
  <i>Overview of Python concepts covered from Basics to Intermediate level</i>
</p>

<hr>

<h2>📘 Python Basics</h2>

<h3>1. Data Types</h3>
<p>
A data type defines the type of value stored in memory.  
Python automatically identifies the data type based on the value assigned.
</p>
<p><b>Common data types:</b> int, float, string, list, tuple, set, dictionary</p>
<pre><code>x = 10        # int
y = 3.14      # float
name = "Ram"  # string
</code></pre>

<hr>

<h3>2. Variables</h3>
<p>
Variables are names that reference values stored in memory.  
Python variables are dynamically typed and automatically initialized.
</p>
<pre><code>a = 5
b = "Python"
c = a + 10
</code></pre>

<hr>

<h3>3. Print Methods</h3>
<p>
Print methods are used to display output on the screen.
</p>
<pre><code>print("Hello", "World")
print("Hello" + " World")
print("Age is %d" % 25)
print(f"Score is {90}")
</code></pre>

<hr>

<h3>4. Type Conversions</h3>
<p>
Type conversion is used to convert one data type into another.
</p>
<pre><code>int(3.5)        # float → int
float(10)       # int → float
str(100)        # int → string
int("25")       # string → int
</code></pre>

<hr>

<h3>5. Operators in Python</h3>
<p>
Operators perform operations on values and variables.
</p>
<ul>
  <li><b>Arithmetic:</b> +, -, *, /</li>
  <li><b>Assignment:</b> =, +=, -=</li>
  <li><b>Comparison:</b> ==, !=, >, <</li>
  <li><b>Logical:</b> and, or, not</li>
  <li><b>Membership:</b> in, not in</li>
  <li><b>Identity:</b> is, is not</li>
  <li><b>Bitwise:</b> &, |, ^</li>
</ul>
<pre><code>5 > 3
a += 2
"x" in "text"
</code></pre>

<hr>

<h3>6. Strings</h3>
<p>
Strings are immutable sequences of characters stored in memory.
</p>
<pre><code>s = "Python"
s[0]        # indexing
s[1:4]      # slicing
s[::2]      # skipping
</code></pre>

<hr>

<h3>7. Lists</h3>
<p>
Lists are ordered and mutable collections that store references to elements.
</p>
<pre><code>lst = [1, 2, 3]
lst.append(4)
lst[0] = 10
</code></pre>

<hr>

<h3>8. Tuples</h3>
<p>
Tuples are ordered but immutable collections.
</p>
<pre><code>t = (1, 2, 3)
t[1]
# t[1] = 5  ❌ not allowed
</code></pre>

<hr>

<h3>9. Sets</h3>
<p>
Sets are unordered collections of unique elements using hash-based storage.
</p>
<pre><code>s = {1, 2, 3, 3}
# Output: {1, 2, 3}
</code></pre>

<hr>

<h3>10. Dictionary</h3>
<p>
Dictionaries store data as key–value pairs using hashing.
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
While loops execute as long as a condition remains true.
</p>
<pre><code>n = 1
while n <= 5:
    print(n)
    n += 1
</code></pre>

<h4>Break Statement</h4>
<p>
Break is used to exit a loop immediately.
</p>
<pre><code>for i in range(10):
    if i == 5:
        break
    print(i)
</code></pre>

<hr>

<h3>2. Conditional Statements</h3>
<p>
Conditional statements control decision-making in programs.
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
Functions group reusable logic into a single block.
</p>
<pre><code>def add(a, b):
    return a + b
</code></pre>

<p><b>Lambda, map, filter, reduce examples:</b></p>
<pre><code>square = lambda x: x*x
list(map(square, [1,2,3]))
</code></pre>

<hr>

<h3>4. Comprehensions</h3>
<p>
Comprehensions provide a concise way to create collections.
</p>
<pre><code>squares = [x*x for x in range(5)]
data = {x: x*x for x in range(3)}
</code></pre>

<hr>

<h2>✅ Summary</h2>
<ul>
  <li>Strong foundation in Python syntax and data structures</li>
  <li>Clear understanding of control flow and functions</li>
  <li>Prepared for advanced Python, SQL, and real-world projects</li>
</ul>

<p align="center">
  🚀 <b>Next Step:</b> Advanced Python • SQL • Data Analysis • Projects
</p>
