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
