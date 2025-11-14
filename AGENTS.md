# Code Review Agent Rules

Follow the rules strictly in all reviews.

## 🧠 Python Style Rules (Custom)

1. **Rule: Avoid List Comprehensions**  
   In this repository, developers **should NOT use list comprehensions**.  
   Always use regular `for` loops for better readability.

2. **Rule: No Global Variables**  
   Developers **must not define global variables**.  
   All data must be passed as function parameters.

3. **Rule: Require Docstrings**  
   Every function must include a clear docstring describing:  
   - purpose  
   - parameters  
   - return value  

## 🚫 Violation Handling  
The agent must report a violation whenever:  
- a list comprehension is used  
- a global variable is defined  
- a function does not contain a docstring
