1. Line 9 prints: `values added: 20`, no errors. 

2. Line 13 prints: `final result: 20`, no errors.

3. We should not use var because it is function-scoped not block-scoped which could cause it to overwrite other variables and that might potentially cause alot of bugs.

4. Line 9 prints: `values added: 20`, no errors.
5. Line 13 results in an error because the result variable is not accessible outside the if block.
6. This would result in an error because we are trying to reassign a variable which we declared with CONST which makes it illegal to reassign
7. nothing would be printed here because of the same error explained above 
