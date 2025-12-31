<h1 align="center">🐍 Python Learning Roadmap</h1>

<p align="center">
  <i>A complete, beginner-friendly Python guide with definitions, syntax, examples, and practice concepts.</i>
</p>

<hr>

<h2>📘 Python Basics</h2>

<h3>1. Data Types</h3>
<p>
Data types define the <b>kind of value</b> a variable holds and the operations allowed on it.
Python is <b>dynamically typed</b>, so type is decided at runtime.
</p>

<ul>
  <li><b>int</b> – Whole numbers</li>
  <li><b>float</b> – Decimal numbers</li>
  <li><b>str</b> – Text data</li>
  <li><b>list</b> – Ordered, mutable collection</li>
  <li><b>tuple</b> – Ordered, immutable collection</li>
  <li><b>set</b> – Unordered, unique elements</li>
  <li><b>dict</b> – Key–value pairs</li>
</ul>

<pre><code>x = 10
price = 99.5
name = "Python"
</code></pre>

<hr>

<h3>2. Variables</h3>
<p>
Variables act as <b>labels for memory locations</b>. Python variables do not need type declaration.
</p>

<pre><code>a = 5
b = "Hello"
c = a + 10
</code></pre>

<hr>

<h3>3. User Input</h3>
<p>
The <b>input()</b> function is used to take input from the user.
By default, input is of type <b>string</b>.
</p>

<pre><code>name = input("Enter name: ")
age = int(input("Enter age: "))
print(name, age)
</code></pre>

<hr>

<h3>4. Print Methods</h3>
<p>
The <b>print()</b> function displays output to the console.
</p>

<pre><code>print("Hello", "World")
print("Age is %d" % 25)
print(f"Score is {90}")
</code></pre>

<hr>

<h3>5. Type Conversion</h3>
<p>
Converting one data type to another is called type casting.
</p>

<pre><code>int(3.5)
float(10)
str(100)
int("25")
</code></pre>

<hr>

<h3>6. Operators</h3>
<ul>
  <li>Arithmetic: + - * / % //</li>
  <li>Comparison: == != > < >= <=</li>
  <li>Logical: and or not</li>
  <li>Assignment: = += -=</li>
  <li>Membership: in, not in</li>
</ul>

<pre><code>a = 10
b = 5
print(a > b)
</code></pre>

<hr>

<h3>7. Strings</h3>
<p>
Strings are immutable sequences of characters.
</p>

<pre><code>s = "Python"
print(s[0])
print(s[1:4])
print(s[::-1])
</code></pre>

<hr>

<h3>8. Lists</h3>
<p>
Lists are ordered and mutable collections.
</p>

<pre><code>lst = [1, 2, 3]
lst.append(4)
lst.insert(1, 10)
lst.remove(2)
lst.pop()
</code></pre>

<hr>

<h3>9. Tuples</h3>
<p>
Tuples are immutable collections.
</p>

<pre><code>t = (1, 2, 3)
print(t[1])
</code></pre>

<hr>

<h3>10. Sets</h3>
<p>
Sets store unique values and are unordered.
</p>

<pre><code>s = {1, 2, 3, 3}
print(s)
</code></pre>

<hr>

<h3>11. Dictionary</h3>
<p>
Dictionaries store data as key–value pairs.
</p>

<pre><code>d = {"name": "Ram", "age": 25}
print(d["name"])
print(d.keys())
print(d.values())
print(d.items())
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
    if i == 2:
        continue
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

<h4>Types of Arguments</h4>
<pre><code>def greet(name, msg="Hello"):
    print(msg, name)

greet("Ram")
greet("Ram", "Hi")
</code></pre>

<h4>Return vs Print</h4>
<pre><code>def square(x):
    return x * x

result = square(5)
print(result)
</code></pre>

<hr>

<h3>4. Lambda Function</h3>
<pre><code>square = lambda x: x * x
print(square(4))
</code></pre>

<hr>

<h3>5. Comprehensions</h3>

<pre><code>squares = [x*x for x in range(5)]
unique = {x for x in [1,2,2,3]}
data = {x: x*x for x in range(3)}
</code></pre>

<hr>

<h3>6. File Handling</h3>

<pre><code>with open("data.txt", "w") as f:
    f.write("Hello Python")

with open("data.txt", "r") as f:
    print(f.read())
</code></pre>

<hr>

<h3>7. Exception Handling</h3>
<pre><code>try:
    num = int(input("Enter number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
finally:
    print("Execution finished")
</code></pre>

<hr>

<h3>8. Object-Oriented Programming (OOPS)</h3>

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

for animal in (Dog(), Cat()):
    animal.sound()
</code></pre>

<h4>Abstraction</h4>
<pre><code>from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass
</code></pre>

<hr>

<h3>9. pass, None & __main__</h3>

<pre><code>def future_function():
    pass

x = None

def main():
    print("Program Started")

if __name__ == "__main__":
    main()
</code></pre>

<hr>

<h2>🧠 Practice Programs</h2>

<pre><code># Reverse a string
s = "Python"
print(s[::-1])

# Find largest number
nums = [3, 7, 1]
print(max(nums))

# Count vowels
count = 0
for ch in "python":
    if ch in "aeiou":
        count += 1
print(count)
</code></pre>

<hr>

<h2 align="center">🎉 End of Python Learning Roadmap</h2>

<p align="center">
  <b>Happy Coding 🚀</b>
</p>
