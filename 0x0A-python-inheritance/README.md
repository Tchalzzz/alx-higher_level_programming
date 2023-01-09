Inheritance
This project contains some tasks for learning about inheritance in Python.

Tasks To Complete
 0. Lookup
0-lookup.py contains a function that returns the list of available attributes and methods of an object.
 1. My list
1-my_list.py contains a class MyList that inherits from list.
Public instance method: def print_sorted(self): that prints the list, but sorted (ascending sort).
 2. Exact same object
2-is_same_class.py contains a function that returns True if the object is exactly an instance of the specified class; otherwise False.
 3. Same class or inherit from
3-is_kind_of_class.py contains a function that returns True if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class; otherwise False.
 4. Only sub class of
4-inherits_from.py contains a function that returns True if the object is an instance of a class that inherited (directly or indirectly) from the specified class; otherwise False.
 5. Geometry module
5-base_geometry.py contains an empty class BaseGeometry.
 6. Improve Geometry
6-base_geometry.py contains a class BaseGeometry (based on 5-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented.
 7. Integer validator
7-base_geometry.py contains a class BaseGeometry (based on 6-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented.
Public instance method: def integer_validator(self, name, value): that validates value.
 8. Rectangle
8-rectangle.py contains a class Rectangle that inherits from BaseGeometry (7-base_geometry.py).
Instantiation with width and height: def __init__(self, width, height):.
 9. Full rectangle
9-rectangle.py contains a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). (task based on 8-rectangle.py).
Instantiation with width and height: def __init__(self, width, height):.
the area() method must be implemented.
print() should print, and str() should return, the following rectangle description: [Rectangle] <width>/<height>.
 10. Square #1
10-square.py contains a class Square that inherits from Rectangle (9-rectangle.py).
Instantiation with size: def __init__(self, size):.
the area() method must be implemented.
 11. Square #2
11-square.py contains a class Square that inherits from Rectangle (9-rectangle.py).
Instantiation with size: def __init__(self, size):.
the area() method must be implemented.
print() should print, and str() should return, the square description: [Square] <width>/<height>.
 12. My integer
100-my_int.py contains a class MyInt that inherits from int and switches the == and != operators.
 13. Can I?
101-add_attribute.py contains a function that adds a new attribute to an object if it’s possible.
