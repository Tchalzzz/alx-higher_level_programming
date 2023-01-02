More Classes and Objects
This project contains some tasks for learning more about classes and objects in Python.

Tasks To Complete
 0. Simple rectangle
0-rectangle.py contains an empty class Rectangle that defines a rectangle.
 1. Real definition of a rectangle
1-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 0-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
 2. Area and Perimeter
2-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 1-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
 3. String representation
3-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 2-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character #. (if width or height is equal to 0, return an empty string).
 4. Eval is magic
4-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 3-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character #. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
 5. Detect instance deletion
5-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 4-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character #. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted.
 6. How many instances
6-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 5-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Public class attribute number_of_instances that is initialized to 0, incremented by 1 during each new instance instantiation, and decremented by 1 during each instance deletion.
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character #. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted.
 7. Change representation
7-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 6-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Public class attribute number_of_instances that is initialized to 0, incremented by 1 during each new instance instantiation, and decremented by 1 during each instance deletion.
Public class attribute print_symbol that is initialized to #, used as symbol for string representation and can be any type.
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character(s) stored in print_symbol. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted.
 8. Compare rectangles
8-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 7-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Public class attribute number_of_instances that is initialized to 0, incremented by 1 during each new instance instantiation, and decremented by 1 during each instance deletion.
Public class attribute print_symbol that is initialized to #, used as symbol for string representation and can be any type.
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character(s) stored in print_symbol. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted.
Static method def bigger_or_equal(rect_1, rect_2): that returns the biggest rectangle based on the area. Returns rect_1 if both have the same area value.
 9. A square is a rectangle
9-rectangle.py contains a class Rectangle that defines a rectangle by: (based on 8-rectangle.py).
Private instance attribute: width.
Property def width(self): to retrieve it.
Property setter def width(self, value): to set it (width must be an integer and greater than or equal to 0).
Private instance attribute: height.
Property def height(self): to retrieve it.
Property setter def height(self, value): to set it (height must be an integer and greater than or equal to 0).
Public class attribute number_of_instances that is initialized to 0, incremented by 1 during each new instance instantiation, and decremented by 1 during each instance deletion.
Public class attribute print_symbol that is initialized to #, used as symbol for string representation and can be any type.
Instantiation with optional width and height: def __init__(self, width=0, height=0):.
Public instance method: def area(self): that returns the rectangle area.
Public instance method: def perimeter(self): that returns the rectangle perimeter.
print() and str() should print the rectangle with the character(s) stored in print_symbol. (if width or height is equal to 0, return an empty string).
repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval().
Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted.
Static method def bigger_or_equal(rect_1, rect_2): that returns the biggest rectangle based on the area. Returns rect_1 if both have the same area value.
Class method def square(cls, size=0): that returns a new Rectangle instance with width == height == size.
 10. N queens
101-nqueens.py contains a program that solves the N queens problem.
