<pre>
>>> for i in range(4):
... print("I am python")
  File "<stdin>", line 2
    print("I am python")
        ^
IndentationError: expected an indented block
>>> for i in range(4):
...     print("Iam python")
... 
Iam python
Iam python
Iam python
Iam python
</pre>

<pre>
>>> for i in range(1+3):
...    print("I am python")
... 
I am python
I am python
I am python
I am python
</pre>

<li> Print a multiplication table</li>

<li>count controlled Loop<li>
  
 <pre>
 >>> for count in range(4):
...     print(count, end=" ")
... 
0 1 2 3 
</pre>

<pre>
>>> for i in range(1, 5):
...     print(i, end=" ")
... 
1 2 3 4 
</pre>

<li>Augmented Assignment </li>
<pre>
a+=1
</pre>

<li>Traversing the Contents of a Data Sequence </li>
<pre>
>>> list
<class 'list'>
>>> list(range(4))
[0, 1, 2, 3]
>>> list(range(1, 5))
[1, 2, 3, 4]
</pre>

<pre>
>>> for i in [1,2,3,4]:
...     print(i, end=" ")
... 
1 2 3 4
</pre>

<li> Specifying a range</li>

<pre>
>>> list(range(1,9,1))
[1, 2, 3, 4, 5, 6, 7, 8]
>>> list(range(1,9,2))
[1, 3, 5, 7]
</pre>

<li>print even numbers </li>
 
 <li>Loops That Count Down </li>
 
 <pre>
 >>> for i in range(10, 0, -1):
...     print(i, end=" ")
... 
10 9 8 7 6 5 4 3 2 1
 </pre>
 
 <li> Task : Assume that the variable str refers to a string "Python". Write a loop that prints each character in this string, followed by its ASCII value </li>
 
 <li> Formatting Text for Output </li>
 <pre>
 >>> for i in range(5, 10):
...     print(i, 10 ** i)
... 
5 100000
6 1000000
7 10000000
8 100000000
9 1000000000
 </pre>
 
 <pre>
 >>> "%8s" % "Python"
'  Python'
>>> "%-8s" % "Python"
'Python  '
 </pre>
 
 <pre>
 >>> for i in range(6,11):
...     print("%-4d%12d" % (i, 10 ** i))
... 
6        1000000
7       10000000
8      100000000
9     1000000000
10   10000000000
 </pre>
 
<li> .precision </li>
  
<pre>
>>> import math
>>> "%6.3f" % math.pi
' 3.142'
>>> math.pi
3.141592653589793
</pre>
