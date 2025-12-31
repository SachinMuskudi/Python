<h1 align="center">🐍 Python Learning Roadmap</h1>

<p align="center">
  <i>A complete beginner-to-intermediate Python guide with clear explanations, syntax, and examples.</i>
</p>

<hr>

<h2>📘 Python Basics</h2>

<h3>1. Data Types</h3>
<p>
A data type defines the <b>type of value</b> stored in a variable and the <b>operations</b> that can be performed on it.
Python is <b>dynamically typed</b>, meaning type is decided at runtime.
</p>

<ul>
  <li><b>int</b> – whole numbers</li>
  <li><b>float</b> – decimal values</li>
  <li><b>str</b> – text</li>
  <li><b>list</b> – ordered & mutable</li>
  <li><b>tuple</b> – ordered & immutable</li>
  <li><b>set</b> – unordered & unique</li>
  <li><b>dict</b> – key-value pairs</li>
</ul>

<pre><code>x = 10
price = 99.5
name = "Python"
</code></pre>

<hr>

<h3>2. Variables</h3>
<p>
Variables are names that <b>refer to memory locations</b>.
No need to declare data type explicitly.
</p>

<pre><code>a = 5
b = "Hello"
c = a + 10
</code></pre>

<hr>

<h3>3. Print Methods</h3>
<p>
The <b>print()</b> function displays output.
</p>

<pre><code>print("Hello", "World")
print("Age is %d" % 25)
print(f"Score is {90}")
</code></pre>

<hr>

<h3>4. Type Conversion</h3>
<p>
Converting one data type into another.
</p>

<pre><code>int(3.5)
float(10)
str(100)
int("25")
</code></pre>

<hr>

<h3>5. Operators</h3>

<ul>
  <li>Arithmetic: + - * / % //</li>
  <li>Comparison: == != > <</li>
  <li>Logical: and or not</li>
  <li>Assignment: = += -=</li>
  <li>Membership: in, not in</li>
</ul>

<pre><code>a = 10
b = 5
print(a > b)
</code></pre>

<hr>

<h3>6. Strings</h3>
<p>
Strings are immutable sequences of characters.
</p>

<pre><code>s = "Python"
print(s[0])
print(s[1:4])
print(s[::-1])
</code></pre>

<hr>

<h3>7. Lists</h3>
<p>
Lists are ordered and mutable.
</p>

<pre><code>lst = [1, 2, 3]
lst.append(4)
lst[0] = 10
</code></pre>

<hr>

<h3>8. Tuples</h3>
<p>
Tuples are immutable collections.
</p>

<pre><code>t = (1, 2, 3)
print(t[1])
</code></pre>

<hr>

<h3>9. Sets</h3>
<p>
Sets store unique values.
</p>

<pre><code>s = {1, 2, 3, 3}
print(s)
</code></pre>

<hr>

<h3>10. Dictionary</h3>
<p>
Dictionaries store key-value pairs.
</p>

<pre><code>d = {"name": "Ram", "age": 25}
print(d["name"])
</code></pre>

<hr>

<h2>📗 Intermediate Python</h2>

<h3>1. Control Statements</h3>

<h4>For Loop</h4>
<pre><code>for i in range(5):
    print(i)
</code></pre>

<h4>While Loop</h4>
<pre><code>n = 1
while n <= 5:
    print(n)
    n += 1
</code></pre>

<h4>Break & Continue</h4>
<pre><code>for i in range(10):
    if i == 5:
        break
    print(i)
</code></pre>

<hr>

<h3>2. Conditional Statements</h3>
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
Functions are reusable blocks of code.
</p>

<pre><code>def add(a, b):
    return a + b

print(add(2, 3))
</code></pre>

<h4>Lambda Function</h4>
<pre><code>square = lambda x: x * x
print(square(5))
</code></pre>

<hr>

<h3>4. Comprehensions</h3>
<p>
A short way to create collections.
</p>

<h4>List Comprehension</h4>
<pre><code>squares = [x*x for x in range(5)]
</code></pre>

<h4>Set Comprehension</h4>
<pre><code>unique = {x for x in [1,2,2,3]}
</code></pre>

<h4>Dictionary Comprehension</h4>
<pre><code>d = {x: x*x for x in range(5)}
</code></pre>

<hr>

<h3>5. File Handling</h3>

<h4>Write File</h4>
<pre><code>with open("data.txt", "w") as f:
    f.write("Hello Python")
</code></pre>

<h4>Read File</h4>
<pre><code>with open("data.txt", "r") as f:
    print(f.read())
</code></pre>

<hr>

<h3>6. Exception Handling</h3>
<p>
Handles runtime errors safely.
</p>

<pre><code>try:
    a = int(input("Enter number: "))
    print(10 / a)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
finally:
    print("Done")
</code></pre>

<hr>

<h3>7. Object-Oriented Programming (OOPS)</h3>

<h4>Class & Object</h4>
<pre><code>class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print(self.name, self.age)

s1 = Student("Ram", 20)
s1.display()
</code></pre>

<h4>Encapsulation</h4>
<pre><code>class Bank:
    def __init__(self):
        self.__balance = 1000
</code></pre>

<h4>Inheritance</h4>
<pre><code>class Parent:
    def show(self):
        print("Parent")

class Child(Parent):
    pass

c = Child()
c.show()
</code></pre>

<h4>Polymorphism</h4>
<pre><code>class Dog:
    def sound(self):
        print("Bark")

class Cat:
    def sound(self):
        print("Meow")

for a in (Dog(), Cat()):
    a.sound()
</code></pre>

<h4>Abstraction</h4>
<pre><code>from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass
</code></pre>

<hr>

<h2 align="center">🎉 End of Python Learning Roadmap</h2>

<p align="center">
  <b>Happy Coding 🚀</b>
</p>
