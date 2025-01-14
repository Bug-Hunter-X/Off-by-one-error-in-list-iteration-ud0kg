# Off-by-One Error in Dart List Iteration

This example demonstrates a common off-by-one error when iterating over a list in Dart.  The error occurs when accessing an index that is out of bounds, leading to a `RangeError` exception.

The `bug.dart` file contains the erroneous code, while `bugSolution.dart` provides the corrected version.

**Key Learning:** Always ensure your loop conditions accurately reflect the valid index range of your list (0 to length - 1).