# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers:  missing error handling for invalid input.  Specifically, the provided code attempts to parse a user ID from a route parameter without checking if the parameter is a valid number.  This can lead to unexpected crashes if the user ID is not a number.

The `bug.js` file contains the buggy code, while `bugSolution.js` demonstrates the corrected version with proper error handling.