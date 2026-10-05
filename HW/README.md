# Session 06: Homework (HW)

## Overview
This directory contains the homework deliverables for Session 06. The primary focus of this assignment was refactoring existing Python code to adhere strictly to custom project standards using AI tools (Cursor), followed by verification of the exact terminal outputs.

## Contents
* **`original_factorial.py`**: The legacy, unrefactored factorial script from HW-04.
* **`original_largest.py`**: The legacy, unrefactored array maximum search script from HW-04.
* **`hw04_factorial.py`**: Refactored factorial calculation script using `for` loops and f-strings.
* **`hw04_largest.py`**: Refactored array maximum search script.
* **`HW06_Rule_Analysis_Table.pdf`**: Analysis table verifying the AI's adherence to the 8 custom coding rules defined in the project `.mdc` file.

## Achievements
1. **Multi-File Context Refactoring**: Replaced legacy `while` loops with Pythonic `for` loops across multiple scripts simultaneously.
2. **Rule Enforcement**: Enforced rigorous AI refactoring according to an 8-rule `.mdc` file, specifically successfully preventing the AI from hallucinating unrequested features or unnecessary edge-case handling.
3. **Behavioral Integrity**: Confirmed a 100% exact match of the legacy terminal output (`Factorial of 5 = 120` and `Largest element is 89`).

## Rule Analysis Table
| Rule | Followed? | Evidence from AI Output |
| :--- | :---: | :--- |
| **1. Use descriptive variable names** | ✅ Yes | Replaced single-letter variables with descriptive names like `number`, `factorial`, and `largest`. |
| **2. One-line function docstring** | ✅ Yes | Stated that "logic lives in functions with... a one-line docstring". |
| **3. Use f-strings for output** | ✅ Yes | Explicitly noted that "print uses f-strings, not `+` concatenation". |
| **4. No unnamed repeated numbers** | ✅ Yes | Extracted the number 5 into a constant named `NUMBER` because it was used multiple times. |
| **5. No unused imports** | ✅ Yes | Stated there were "No extra imports". |
| **6. No unrequested features** | ✅ Yes | Confirmed it added "No extra features", strictly adhering to the prompt without adding unnecessary error handling. |
| **7. Use type hints** | ✅ Yes | Confirmed that "logic lives in functions with type hints". |
| **8. Avoid while loops** | ✅ Yes | Stated that "while loops are for loops" now. |
