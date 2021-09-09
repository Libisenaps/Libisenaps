# List
## Types of list
* Append() method
* Clear() method
* Copy() method
* Count() method
* Extend() method
* Index() method
* Insert() method
* Pop() method
* Remove() method
* Reverse() method
* Sort()d() method

``` python
### Append() method
a=["apple","mango","orange"]
b=["ford","bmw","rollsroyce"]
a.append(b)

>>a=['apple','mango','orange',['ford','bmw','rollsroyce']]
```
``` python
### Clear() method
a=["apple","banana","orange"]
a.clear()

>>a=[]
```
``` python
### Copy() method
a=["apple","banana","orange"]
a.copy()

>>a=['apple','banana','orange']
```
``` python
### Count() method
a=["apple","banana","apple","orange"]
x=a.count("apple")

>>x=2
```
``` python
### Extend() method
a=["apple","mango","orange"]
b=["ford","bmw","rollsroyce"]
a.extend(b)

>>a=['apple','mango','orange','ford','bmw','rollsroyce']
```
``` python
### Index() method
a=["apple","mango","orange"]
x=a.index("orange")

>>x=2
```
``` python
### Insert() method
a=["apple","mango","orange"]
x=a.insert(3,"gauva")

>>x=['apple','mango','orange','gauva']
```
``` python
### Pop() method
a=["apple","mango","orange"]
a.pop(1)

>>a=['apple','orange']
```
``` python
### Remove() method
a=["apple","mango","orange"]
a.remove("mango")

>>a=['apple','orange']
```
``` python
### Reverse() method
a=["apple","mango","orange"]
a.reverse()

>>a=['orange','mango','apple']
```
``` python
### Sort() method
a=["apple","mango","banana","gauva","orange"]
a.sort()

>>a=['apple','banana','gauva','mango','orange']
```