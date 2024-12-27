# Silent Failure: Accessing Non-Existent HTML Attributes

This example demonstrates a subtle error in HTML/JavaScript where attempting to access a non-existent attribute on an HTML element doesn't throw an error, but instead silently returns 'undefined'.  This can lead to unexpected behavior and difficult-to-debug issues.

The `bug.html` file shows the problematic code, and `bugSolution.html` provides a solution using robust error checking.

## Bug

The bug lies in accessing a non-existent attribute (nonExistentAttribute).  Instead of throwing an error, it returns undefined which can be difficult to detect.