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
my_sbj[0]
Out[50]: 'c++'

my_sbj[1:3]
Out[51]: ('Java', 'Python')

list1=[1,'a',2,7]

list1
Out[53]: [1, 'a', 2, 7]

list1[0]
Out[56]: 1

list1[0:3]
Out[57]: [1, 'a', 2]

type(list1)
Out[58]: list
#append()

list1.append("x")

list1
Out[61]: [1, 'a', 2, 7, 'x']

list1.extend(['s','g'])


list1
Out[63]: [1, 'a', 2, 7, 'x', 's', 'g']

list1
Out[63]: [1, 'a', 2, 7, 'x', 's', 'g']

list2=[8,9]

list1.extend(list2)

list1
Out[66]: [1, 'a', 2, 7, 'x', 's', 'g', 8, 9]
list1.insert(1,'tt')

list1
Out[69]: [1, 'tt', 'a', 2, 7, 'x', 's', 'g', 8, 9]
list1.pop()
Out[70]: 9

list1.pop(1)
Out[71]: 'tt'

list1
Out[73]: [1, 'a', 2, 7, 'x', 's', 'g', 8]

mydict={1:'Apple', 2:'Mango', 3:'Orange'}

mydict
Out[78]: {1: 'Apple', 2: 'Mango', 3: 'Orange'}

mydict1 = {'name':'John', 1:[2,4,6]}

mydict1

Out[85]: {'name': 'John', 1: [2, 4, 6]}

emp = {'name':'JOhn', 'Add':['xyx','abc']}

emp
Out[87]: {'name': 'JOhn', 'Add': ['xyx', 'abc']}
len(mydict)
Out[89]: 3

len(emp)
Out[90]: 2
mydict1.keys()
Out[91]: dict_keys(['name', 1])

mydict1.keys()
Out[91]: dict_keys(['name', 1])

mydict1.values()
Out[92]: dict_values(['John', [2, 4, 6]])

mydict1.items()
Out[93]: dict_items([('name', 'John'), (1, [2, 4, 6])])

mydict1.update({3:'profile'})

mydict1
Out[97]: {'name': 'John', 1: [2, 4, 6], 3: 'profile'}

n [97]: mydict1
Out[97]: {'name': 'John', 1: [2, 4, 6], 3: 'profile'}

mydict1.pop('name')
Out[98]: 'John'

mydict1
Out[99]: {1: [2, 4, 6], 3: 'profile'}

my_set1 = {1,2,3,4,4,5,5,6}

my_set1
Out[102]: {1, 2, 3, 4, 5, 6}

my_set2={7,5,4,4,6}

my_set1 | my_set2
Out[104]: {1, 2, 3, 4, 5, 6, 7}

my_set1 & my_set2
Out[105]: {4, 5, 6}



</pre>
