# Polygon Area Calculator

A Python object-oriented programming project that implements `Rectangle` and `Square` classes.

The `Square` class inherits from the `Rectangle` class and extends its functionality while maintaining equal width and height.

## Features

* Create and manipulate rectangles and squares.
* Calculate the area of a shape.
* Calculate the perimeter of a shape.
* Calculate the diagonal length.
* Generate a text-based representation of the shape using `*`.
* Determine how many times one shape can fit inside another.
* Demonstrate inheritance and method overriding using Python OOP.

## Classes

### Rectangle

The `Rectangle` class includes:

* `set_width()`
* `set_height()`
* `get_area()`
* `get_perimeter()`
* `get_diagonal()`
* `get_picture()`
* `get_amount_inside()`
* `__str__()`

### Square

The `Square` class inherits from `Rectangle` and includes:

* `set_side()`
* Overridden `set_width()`
* Overridden `set_height()`
* Overridden `__str__()`

## Example

```python
rect = Rectangle(10, 5)
print(rect.get_area())

rect.set_height(3)
print(rect.get_perimeter())
print(rect)
print(rect.get_picture())

sq = Square(9)
print(sq.get_area())

sq.set_side(4)
print(sq.get_diagonal())
print(sq)
print(sq.get_picture())

rect.set_height(8)
rect.set_width(16)
print(rect.get_amount_inside(sq))
```

### Output

```text
50
26
Rectangle(width=10, height=3)
**********
**********
**********

81
5.656854249492381
Square(side=4)
****
****
****
****

8
```

## Concepts Practiced

* Object-Oriented Programming
* Classes and Objects
* Inheritance
* Method Overriding
* Constructors
* Instance Attributes
* Encapsulation
* Mathematical calculations
* Python string formatting

## Technologies

* Python 3

## Project

This project was completed as part of a Python programming exercise focused on Object-Oriented Programming and inheritance.
