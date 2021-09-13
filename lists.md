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
* Sort() method

### Append() method

``` python
a=["apple","mango","orange"]
b=["ford","bmw","rollsroyce"]
a.append(b)
==>a=['apple','mango','orange',['ford','bmw','rollsroyce']]
```


### Clear() method
``` python
a=["apple","banana","orange"]
a.clear()
==> a=[]
```

### Copy() method
``` python
a=["apple","banana","orange"]
a.copy()

>>a=['apple','banana','orange']
```

### Count() method
``` python
a=["apple","banana","apple","orange"]
x=a.count("apple")

>>x=2
```

### Extend() method
``` python
a=["apple","mango","orange"]
b=["ford","bmw","rollsroyce"]
a.extend(b)

>>a=['apple','mango','orange','ford','bmw','rollsroyce']
```

### Index() method
``` python
a=["apple","mango","orange"]
x=a.index("orange")

>>x=2
```

### Insert() method
``` python
a=["apple","mango","orange"]
x=a.insert(3,"gauva")

>>x=['apple','mango','orange','gauva']
```

### Pop() method
``` python
a=["apple","mango","orange"]
a.pop(1)

>>a=['apple','orange']
```

### Remove() method
``` python
a=["apple","mango","orange"]
a.remove("mango")

>>a=['apple','orange']
```

### Reverse() method
``` python
a=["apple","mango","orange"]
a.reverse()

>>a=['orange','mango','apple']
```

### Sort() method
``` python
a=["apple","mango","banana","gauva","orange"]
a.sort()

>>a=['apple','banana','gauva','mango','orange']
```
