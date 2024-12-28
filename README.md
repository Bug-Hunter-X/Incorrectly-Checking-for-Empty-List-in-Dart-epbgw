# Incorrect Empty List Check in Dart

This repository demonstrates a common error in Dart: incorrectly checking if a list is empty. The provided code checks if the list variable itself is null instead of checking if the list is empty.

The solution demonstrates the correct way to check for an empty list using the `isEmpty` property.

## Bug
The `bug.dart` file contains the erroneous code. The code attempts to check if a list is empty using the `== null` comparison. This only works if the list variable itself is null (uninitialized), not if the list is empty but has been initialized.

## Solution
The `bugSolution.dart` file contains the corrected code. It uses the `isEmpty` property to accurately determine if the list is empty.