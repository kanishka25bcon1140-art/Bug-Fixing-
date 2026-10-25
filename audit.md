# Testing and Debugging Audit

## Objective

To identify and fix bugs in a Python utility script using unit testing and AI-assisted debugging with Cursor AI.

## Testing Process

1. Created an initial Python implementation containing logical errors.
2. Wrote nine unit tests to verify average calculation, pass/fail checking, and grade assignment.
3. Executed the tests and observed failures in the original implementation (**RED**).
4. Used Cursor AI to identify the errors and correct the program logic (**FIX**).
5. Executed the tests again to verify the corrected implementation (**GREEN**).

## Bugs Identified

* Incorrect average calculation.
* Division-by-zero risk when calculating the average of an empty list.
* Incorrect pass/fail boundary handling.
* Incorrect grade classification due to the order of conditions.

## Final Result

All nine unit tests passed successfully after the corrections were applied.

## Verification

**Command used:**

```bash
python -m unittest -v test_student_utils.py
```

**Expected result:**

```text
Ran 9 tests

OK
```

## Conclusion

The RED → FIX → GREEN cycle provided a systematic approach to identifying errors, correcting the program, and verifying its functionality. Unit testing and Cursor AI helped improve the reliability and correctness of the Python utility functions.
