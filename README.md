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

