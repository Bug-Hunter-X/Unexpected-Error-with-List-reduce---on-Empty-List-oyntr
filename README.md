# Dart List.reduce() on Empty List Bug

This repository demonstrates an uncommon error that can occur when using the `reduce` method on an empty list in Dart.  The `reduce` method requires at least one element to perform the reduction; if the list is empty, it throws an exception.  The example shows both the incorrect and the correct approach.

## Solution

The solution involves adding a check to verify that the list is not empty before calling `reduce`.  This prevents the exception from being thrown and ensures that the code handles empty lists gracefully.  See `bugSolution.dart` for implementation details.