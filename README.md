# Array
from numpy import array
cars=array
cars=["ford", "bmw", "honda"] #initalazing array
print(cars[2])
print(len(cars))# Its shows no of elements in cars
for x in cars:#loop of an array
    print(x)
cars.append("audi")# Adding elements in cars
print(cars)
cars.pop()#removing element in array without index
print(cars)
cars.pop(2)#removing element in array with index
print(cars)
cars.remove("bmw")#removing values in cars
print(cars)
bikes=["cbr","duke","pulsar","duke"]
cars.extend(bikes)#Adding elements in the array
print(cars)
print(cars.count("pulsar"))
print(type(cars))

"""Array has built in methods:
1.append()-Adds a element at the end of the list:
2.clear()-Removes all the elements from the list:
3.count()-Returns the number of elements with the specified value
4.index()-Returns the index of the first elements with specified value
5.insert()-Adds an elements at the specified position
6.pop()-Removes the elements in the specified position
7.remove()-Returns the first items in the specified value
8.reverse()-Reverse the order of the list
9.sort()-Sorts the list
10.copy()-Returns a copy of the list
11.extend()-add the elements of the list(or any iterables) to the end of the current list
"""
"""creating an array"""

