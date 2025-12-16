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
Strings are sequences of characters enclosed in quo
