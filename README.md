<pre>
a=2

b=3

a=b

b+a
Out[4]: 6

3=5
  File "<ipython-input-5-6a7ff31f369c>", line 1
    3=5
       ^
SyntaxError: can't assign to literal

3a=4
  File "<ipython-input-6-275b7d6d7641>", line 1
    3a=4
     ^
SyntaxError: invalid syntax

d1=3
a,b,c=1,2,5
a
Out[9]: 1
b
Out[10]: 2
c
Out[11]: 5

x="rk"
y='rk'

x
Out[16]: 'rk'
y
Out[17]: 'rk'

story_name="harry"

story_no=12

print("welcome to " + story_name + " it sno is ", story_no)
welcome to harry it sno is  12

a=2

b=3

c=a+b

c
Out[26]: 5

x=10

x/5
Out[28]: 2.0

num1=3

num2=5

print("num1 > mum2 ?", num1>num2)
num1 > mum2 ? False

x=2

y=3

print("x and y is ", x and y)
x and y is  3

print("x and y is ", x or y)
x and y is  2

print("Bitwise XOR ", x^y)
Bitwise XOR  4

print("Bitwise XOR ", x|y)
Bitwise XOR  6

print("Bitwise XOR ", x>>2)
Bitwise XOR  1

print("Bitwise XOR ", x<<2)
Bitwise XOR  24

identity operator
a=5

a is 5
Out[12]: True

a is 6
Out[13]: False

a is not 5
Out[14]: False
x=[1,2,3,4,5]

4 in x
Out[16]: True

7 in x
Out[17]: False
(4 + 2 ** 2) / 2 + (4 * 3 +6 / 2)
Out[18]: 19.0

a=3+12j

b=4+25j

a+b
Out[24]: (7+37j)

str1 = "hello"

str2 = "welcome"

print(str1+str2)
hellowelcome

print(str1 * 3)
hellohellohello

print(str1,  str2)
hello welcome

print(str1 + str2)
hellowelcome

print(str1   +   str2)
hellowelcome

print(str1*2)
hellohello

print(str1*2, str2*3)
hellohello welcomewelcomewelcome

print(str1[2:4])
ll

print(str1[2])
l

tuple
my_sbj=('c++', 'Java', 'Python', 'R')

my_sbj
Out[43]: ('c++', 'Java', 'Python', 'R')
print(my_sbj + ('Dart', 'Swift'))
('c++', 'Java', 'Python', 'R', 'Dart', 'Swift')
x_sub=('datasci','cloud')

print(my_sbj + x_sub)
('c++', 'Java', 'Python', 'R', 'datasci', 'cloud')
print(x_sub * 2)
('datasci', 'cloud', 'datasci', 'cloud')

</pre>
