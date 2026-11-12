
# Purpose
Create tests that check whether code behaves as expected.

# Steps
1.  Read the code and identify the behavior that needs testing.
2.  Write a single test using Python.

# Test quality
- A good test fails on the current code and passes once the bug is fixed.
- Avoid unnecessary complicated tests.

# Rules
- The test name should start with 'test_'

# Example
def test_is_adult_at_18():
    assert is_adult(18) == True
