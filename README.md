# Dart Out-of-Bounds List Access Bug

This repository demonstrates a common error in Dart programming: accessing an element in a list using an index that is out of bounds.  This can lead to an `RangeError` exception.

The `bug.dart` file contains the erroneous code.  The `bugSolution.dart` file provides a corrected version.

This is a simple example, but the principle applies to more complex scenarios where the index might be calculated dynamically. Always check your indexes before accessing list elements to prevent runtime errors.