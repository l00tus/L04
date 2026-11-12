# Bug reports for exercise1.py

Line: 3  
Problem: is_even returns True for odd numbers but the docstring says "true for even numbers".  
Example: is_even(3) returns True, expected False.  
Fix: return n % 2 == 0

Line: 8  
Problem: rectangle_area returns the sum of width and height, not the product.  
Example: rectangle_area(3, 4) returns 7, expected 12.  
Fix: return width * height

Line: 13  
Problem: double returns n + 2, not twice the number.  
Example: double(5) returns 7, expected 10.  
Fix: return n * 2
