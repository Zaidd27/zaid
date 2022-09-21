# zaid
#Assignment 1:

# List

list = ["TeachNook",5,True,3.4]
print(list)
list.append("September")
list.insert(5,"Data Science")
list.remove(3.4)
print(list)

> ['TeachNook', 5, True, 3.4]
  ['TeachNook', 5, True, 'September', 'Data Science']

  
# Tuple

tuple1=("TeachNook",5,True,3.4)
tuple2=("Good",10,7.5,False)
print(tuple1+tuple2)

> ('TeachNook', 5, True, 3.4, 'Good', 10, 7.5, False)


# Dict

dict={"name":"Abc", "age":16, "Student":True, "Count":4}
print(dict)
dict["name"]="Jake"
dict["Place"]="New York"
dict.pop("Count")
print(dict)

> {'name': 'Abc', 'age': 16, 'Student': True, 'Count': 4}
  {'name': 'Jake', 'age': 16, 'Student': True, 'Place': 'New York'}  
  

# Slicing

x = "I am going to slice this sentence in python"
print(x)
print (x[0:10])
print (x[-15:-1])
print (x[3:20:2])

> I am going to slice this sentence in python
  I am going
  tence in pytho
  mgigt lc 



# ASSIGNMENT 2:

# Frozen set

x = frozenset(['a','b','c'])
print(x)

> frozenset({'a', 'c', 'b'})
