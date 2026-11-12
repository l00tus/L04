
# Purpose
Inspect code or a feature and identify likely bugs. Keep the review
simple and practical.

# Steps
1.  Read the relevant code and understand what it should do.
2.  Look for incorrect logic, missing checks, edge cases, and possible crashes.
3.  Check how errors and unusual inputs are handled.
4.  Report only issues that have a clear reason or reproducible example.

# Report format (example)
Line: 12
Problem: is_adult returns False for someone who is exactly 18, but the docstring says "18 or older".
Example: is_adult(18) returns False, expected True.
Fix: return age >= 18

# Rules
-   Do not change code.
-   Keep reports short and clear.
