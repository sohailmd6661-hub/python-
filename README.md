# python

<h1>Basic Python – Definitions & Examples</h1>

<hr>

<h2>What is Python?</h2>
<p>
Python is a high-level, interpreted, and object-oriented programming language.
It is easy to learn and widely used for web development, data science,
automation, artificial intelligence, and more.
</p>

<hr>

<h2>Variables</h2>
<p>
A variable is used to store data values in memory.
</p>

<h3>Example:</h3>
<pre>
x = 10
name = "Sohail"
print(x)
print(name)
</pre>

<hr>

<h2>Data Types</h2>
<p>
Data types specify the type of value a variable holds.
</p>

<ul>
  <li><b>int</b> – Integer numbers</li>
  <li><b>float</b> – Decimal numbers</li>
  <li><b>str</b> – Text data</li>
  <li><b>list</b> – Collection of items</li>
  <li><b>tuple</b> – Immutable collection</li>
  <li><b>set</b> – Unordered collection</li>
  <li><b>dict</b> – Key-value pairs</li>
</ul>

<h3>Example:</h3>
<pre>
a = 10
b = 10.5
c = "Python"
print(type(a), type(b), type(c))
</pre>

<hr>

<h2>String</h2>
<p>
A string is a sequence of characters enclosed in single or double quotes.
</p>

<h3>Example:</h3>
<pre>
s = "python"
print(s.upper())
print(len(s))
</pre>

<hr>

<h2>List</h2>
<p>
A list is a mutable collection that can store multiple values.
</p>

<h3>Example:</h3>
<pre>
numbers = [1, 2, 3, 4]
numbers.append(5)
print(numbers)
</pre>

<hr>

<h2>Tuple</h2>
<p>
A tuple is an immutable collection of items.
</p>

<h3>Example:</h3>
<pre>
t = (10, 20, 30)
print(t)
</pre>

<hr>

<h2>Set</h2>
<p>
A set is an unordered collection of unique elements.
</p>

<h3>Example:</h3>
<pre>
s = {1, 2, 3, 3}
print(s)
</pre>

<hr>

<h2>Dictionary</h2>
<p>
A dictionary stores data in key-value pairs.
</p>

<h3>Example:</h3>
<pre>
student = {
  "name": "Sohail",
  "age": 22,
  "course": "Python"
}
print(student["name"])
</pre>

<hr>

<h2>For Loop</h2>
<p>
A for loop is used to repeat a block of code for a fixed number of times.
</p>

<h3>Example:</h3>
<pre>
for i in range(1, 6):
    print(i)
</pre>

<hr>

<h2>While Loop</h2>
<p>
A while loop runs as long as a condition is true.
</p>

<h3>Example:</h3>
<pre>
i = 1
while i <= 5:
    print(i)
    i += 1
</pre>

<hr>

<h2>Function</h2>
<p>
A function is a reusable block of code that performs a specific task.
</p>

<h3>Example:</h3>
<pre>
def add(a, b):
    return a + b

result = add(10, 20)
print(result)
</pre>

<hr>

<h2>Conclusion</h2>
<p>
This document covers basic Python concepts with simple definitions and examples,
making it easy for beginners to understand and practice.
</p>

<h1>Intermediate Python</h1>

<h2>🔹 Definition</h2>
<p>
A loop is used to execute a block of code repeatedly until a condition is met.
</p>

<h2>🔹 Example</h2>

<pre><code class="language-python">
for i in range(1, 6):
    print(i)
</code></pre>

<hr>

<h2>🔹 Definition</h2>
<p>
A function is a reusable block of code that performs a specific task.
</p>

<h2>🔹 Example</h2>

<pre><code class="language-python">
def add(a, b):
    return a + b

print(add(5, 3))
</code></pre>

<hr>

<h2>🔹 Definition</h2>
<p>
List comprehension provides a concise way to create lists.
</p>

<h2>🔹 Example</h2>

<pre><code class="language-python">
numbers = [1, 2, 3, 4]
squares = [n*n for n in numbers]
print(squares)
</code></pre>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Python Exception Handling</title>
</head>
<body>

<h1>Python Exception Handling</h1>

<p>
Exception handling is used to handle runtime errors so that the normal flow of the program is not interrupted.
</p>

<h2>What is an Exception?</h2>
<p>
An exception is an error that occurs during the execution of a program.
</p>

<h2>Common Python Exceptions</h2>
<ul>
    <li>ZeroDivisionError</li>
    <li>ValueError</li>
    <li>NameError</li>
    <li>TypeError</li>
    <li>IndexError</li>
</ul>

<h2>Example: try and except</h2>

<pre>
try:
    a = 10
    b = 0
    print(a / b)
except ZeroDivisionError:
    print("Cannot divide by zero")
</pre>

<h2>Example: try, except, else</h2>

<pre>
try:
    x = 10
    y = 2
    print(x / y)
except ZeroDivisionError:
    print("Error")
else:
    print("Division successful")
</pre>

<h2>Example: try, except, finally</h2>

<pre>
try:
    n = 5
    s = 0
    for i in range(1, n):
        if n % i == 0:
            s += i
    if s == n:
        print("Perfect Number")
    else:
        print("Not a Perfect Number")
except Exception as e:
    print(e)
finally:
    print("Done")
</pre>

<h2>Why use Exception Handling?</h2>
<ul>
    <li>Prevents program crash</li>
    <li>Handles runtime errors</li>
    <li>Makes code safe and readable</li>
</ul>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exception Handling in Python</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 6px;
            overflow-x: auto;
        }
        ul {
            margin-left: 20px;
        }
    </style>
</head>
<body>

<h1>Exception Handling in Python</h1>

<h2>What is Exception Handling?</h2>
<ul>
    <li>Exception means <b>Error</b></li>
    <li>It prevents program termination</li>
    <li>Handled using <b>try, except, else, finally</b></li>
</ul>

<h2>Syntax Error</h2>
<pre><code>
190S = 100
print(190S)
</code></pre>

<h2>ZeroDivisionError</h2>
<pre><code>
50 / 0
</code></pre>

<h2>NameError</h2>
<pre><code>
AREA = "HYDERABAD"
print(area)
</code></pre>

<h2>ValueError</h2>
<pre><code>
a = "1882S"
print(int(a))
</code></pre>

<h2>IndentationError</h2>
<pre><code>
for i in range(1, 11):
print(i)
</code></pre>

<h2>FileNotFoundError</h2>
<pre><code>
with open("sohail.txt", "r") as f:
    print(f.read())
</code></pre>

<h2>Real Time Example (try-except)</h2>
<pre><code>
try:
    a = 1067
    b = 2009
    print(b / a)
except Exception as e:
    print(e)
</code></pre>

<h2>Perfect Number with Exception Handling</h2>
<pre><code>
n = 5
s = 0

try:
    for i in range(1, n):
        if n % i == 0:
            s += i
    if s == n:
        print("Perfect Number")
    else:
        print("Not a Perfect Number")
except Exception as e:
    print("An error occurred:", e)
finally:
    print("Done")
</code></pre>

<h2>Practice Errors</h2>

<h3>ZeroDivisionError</h3>
<pre><code>
a = 45
b = 0
print(a / b)
</code></pre>

<h3>ValueError</h3>
<pre><code>
a = "4k"
b = int(a)
print(b)
</code></pre>

<h3>NameError</h3>
<pre><code>
a = "sohail"
print(h)
</code></pre>

<h3>TypeError</h3>
<pre><code>
a = 10
b = "5"
print(a + b)
</code></pre>

<h3>IndexError</h3>
<pre><code>
a = [10, 20, 30]
print(a[5])
</code></pre>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>class_object_self</title>

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <style type="text/css">
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 20px;
            background-color: #ffffff;
        }
        h1, h2, h3 {
            color: #333;
        }
        pre {
            background: #f5f5f5;
            padding: 10px;
            overflow-x: auto;
            border-radius: 5px;
        }
        code {
            color: #c7254e;
        }
    </style>
</head>

<body>

<h1>Class, Object & self (Python)</h1>

<h2>Example 1: Class and Object</h2>

<pre><code>
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def show(self):
        print(self.name, self.age)

s1 = Student("Sohail", 22)
s1.show()
</code></pre>

<h2>Example 2: Using self keyword</h2>

<pre><code>
class Employee:
    def details(self, name, salary):
        self.name = name
        self.salary = salary

    def display(self):
        print(self.name, self.salary)

e1 = Employee()
e1.details("Rahul", 25000)
e1.display()
</code></pre>

<h2>Explanation</h2>
<ul>
    <li><b>Class</b>: Blueprint of an object</li>
    <li><b>Object</b>: Instance of a class</li>
    <li><b>self</b>: Refers to current object</li>
</ul>

</body>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>OOPS Constructor Programs</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
            padding: 30px;
        }
        h2 {
            color: #333;
        }
        pre {
            background-color: #1e1e1e;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 6px;
            overflow-x: auto;
        }
    </style>
</head>
<body>

<h2>Constructor without parameters</h2>
<pre><code>
class MECH:
    f = 20

    def __init__(self):
        print('Good Morning')

anil = MECH()
</code></pre>

<h2>Constructor with parameters</h2>
<pre><code>
class MECH:
    f = 20

    def __init__(self, a):
        print('Good Morning', a)

anil = MECH(10)
</code></pre>

<h2>Constructor with multiple methods</h2>
<pre><code>
class CSE:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def addition(self):
        print(self.a + self.b)

    def subtraction(self):
        print(self.a - self.b)

anil = CSE(6, 8)
anil.addition()
anil.subtraction()
</code></pre>

<h2>Calculator without constructor</h2>
<pre><code>
class CALCULATOR:
    a = 6
    b = 8

    def addition(self):
        print(self.a + self.b)

    def subtraction(self):
        print(self.a - self.b)

    def multiply(self):
        print(self.a * self.b)

    def division(self):
        print(self.a / self.b)

anil = CALCULATOR()
anil.addition()
anil.subtraction()
anil.multiply()
anil.division()
</code></pre>

<h2>Calculator with constructor</h2>
<pre><code>
class CALCULATOR:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def addition(self):
        print(self.a + self.b)

    def subtraction(self):
        print(self.a - self.b)

    def multiply(self):
        print(self.a * self.b)

    def division(self):
        print(self.a / self.b)

anil = CALCULATOR(6, 8)
anil.addition()
anil.subtraction()
anil.multiply()
anil.division()
</code></pre>

<h2>Prime Number Program</h2>
<pre><code>
class PRIME:
    def calculation(self, a, b):
        for i in range(a, b):
            if i > 1:
                for j in range(2, i):
                    if i % j == 0:
                        print(f'Not Prime : {i}')
                        break
                else:
                    print(f'Prime : {i}')

anil = PRIME()
anil.calculation(1, 101)
