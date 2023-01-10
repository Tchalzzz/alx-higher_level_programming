This project contains some tasks for learning about input/output routines in Python.

Tasks To Complete
 0. Read file
0-read_file.py contains a function that reads a test file (UTF8) and prints it to stdout.
 1. Write to a file
1-write_file.py contains a function that writes a string to a text file (UTF8) and returns the number of characters written.
 2. Append to a file
2-append_write.py contains a function that appends a string at the end of a text file (UTF8) and returns the number of characters added.
 3. To JSON string
3-to_json_string.py contains a function that returns the JSON representation of an object (string).
 4. From JSON string to Object
4-from_json_string.py contains a function that returns an object (Python data structure) represented by a JSON string.
 5. Save Object to a file
5-save_to_json_file.py contains a function that writes an Object to a text file, using a JSON representation.
 6. Create object from a JSON file
6-load_from_json_file.py contains a function that creates an Object from a “JSON file”.
 7. Load, add, save
7-add_item.py contains a script that adds all arguments to a Python list, and then save them to a file named add_item.json.
 8. Class to JSON
8-class_to_json.py contains a function that returns the dictionary description with simple data structure (list, dictionary, string, integer and boolean) for JSON serialization of an object.
 9. Student to JSON
9-student.py contains a class Student that defines a student by:
Public instance attributes: first_name, last_name, and age.
Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.
Public method def to_json(self): that retrieves a dictionary representation of a Student instance (same as 8-class_to_json.py).
 10. Student to JSON with filter
10-student.py contains a class Student that defines a student by: (based on 9-student.py).
Public instance attributes: first_name, last_name, and age.
Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.
Public method def to_json(self, attrs=None): that retrieves a dictionary representation of a Student instance (same as 8-class_to_json.py). If attrs is a list of strings, only attribute names contained in this list must be retrieved, otherwise all attributes must be retrieved.
 11. Student to disk and reload
11-student.py contains a class Student that defines a student by: (based on 10-student.py).
Public instance attributes: first_name, last_name, and age.
Instantiation with first_name, last_name, and age: def __init__(self, first_name, last_name, age):.
Public method def to_json(self, attrs=None): that retrieves a dictionary representation of a Student instance (same as 8-class_to_json.py). If attrs is a list of strings, only attribute names contained in this list must be retrieved, otherwise all attributes must be retrieved.
Public method def reload_from_json(self, json): that replaces all attributes of the Student instance. json is a dictionary whose key-value pairs correspond to the public attribute names and values of the Student instance.
 12. Pascal's Triangle
12-pascal_triangle.py contains a function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n.
 13. Search and update
100-append_after.py contains a function that inserts a line of text to a file, after each line containing a specific string.
 14. Log parsing
101-stats.py contains a script that reads stdin line by line and computes metrics:.
Input format: <IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>.
Each 10 lines and after a keyboard interruption (CTRL + C), prints those statistics since the beginning according to the following requirements:
Total file size: File size: <total size>. Where <total size> is the sum of all previous <file size>.
Number of lines by status code. Possible status codes are 200, 301, 400, 401, 403, 404, 405, and 500. Format: <status code>: <number>. Where <number> is the number of times a status code has appeared. The status codes should be printed in ascending order.
Footer
