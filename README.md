#  Fixing a Buggy Python Script Using AI

## 📌 Project Overview

This project demonstrates how to identify, debug, and fix errors in a Python program using unit testing and AI-assisted debugging with Cursor AI. It follows the **RED → FIX → GREEN** cycle to ensure that the program works as expected after correcting the errors.

## 📂 Project Files

* `student_utils.py` — Contains functions to calculate average marks, check passing status, and assign grades.
* `test_student_utils.py` — Contains unit tests to verify the correctness of the functions.
* `audit.md` — Documents the testing process and debugging results.
* `bug_notes.md` — Describes the identified bugs and their corresponding fixes.
* `README.md` — Provides project information and instructions.

## 🐛 Bugs Identified and Fixed

1. **Incorrect Average Calculation:** Fixed an incorrect formula used to calculate the average marks.
2. **Division by Zero:** Added appropriate handling for an empty marks list to prevent division-by-zero errors.
3. **Passing Criteria:** Corrected the logic for determining whether a student has passed or failed.
4. **Incorrect Grade Classification:** Fixed the order of grade conditions to ensure marks are classified correctly.

## 🧪 Testing

The project uses Python's built-in `unittest` framework to test the functions.

**Run the tests using:**

```bash
python -m unittest -v test_student_utils.py
```

**Expected Result:**

```text
Ran 9 tests

OK
```

All nine tests should pass when the implementation matches the test expectations.

## 🔄 RED → FIX → GREEN Cycle

* 🔴 **RED:** Run the tests against the original buggy code and identify failures.
* 🛠️ **FIX:** Use Cursor AI to identify the errors and correct the program logic.
* 🟢 **GREEN:** Run the tests again and verify that all nine tests pass.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Testing Framework:** unittest
* **AI-Assisted Debugging:** Cursor AI

## 🎯 Learning Objectives

* Understand common logical errors in Python programs.
* Learn how to write and execute unit tests.
* Practise debugging with AI-assisted development tools.
* Verify program correctness using automated testing.

## 🏁 Conclusion

This project demonstrates how unit testing and Cursor AI can help identify and correct programming errors. The RED → FIX → GREEN approach provides a systematic way to debug code and verify that the corrected implementation behaves as expected.
