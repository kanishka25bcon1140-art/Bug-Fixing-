# Bug Notes

This file documents the bugs identified in the Python utility program, their causes, and the fixes applied.

## Bugs Identified and Fixed

| Bug                        | Cause                                                  | Fix                                                          |
| -------------------------- | ------------------------------------------------------ | ------------------------------------------------------------ |
| Incorrect average          | Divided by `len(marks) - 1` instead of `len(marks)`    | Corrected the average calculation formula.                   |
| Single-mark error          | Incorrect denominator caused an inaccurate result      | Corrected the denominator to calculate the average properly. |
| Pass boundary error        | Used `mark > PASS_MARK` instead of `mark >= PASS_MARK` | Changed the condition to `mark >= PASS_MARK`.                |
| Wrong grade classification | Checked lower grade thresholds before Distinction      | Reordered the conditions from highest grade to lowest.       |

## Testing and Verification

The program was tested using Python's built-in `unittest` framework.

**Command:**

```bash
python -m unittest -v test_student_utils.py
```

**Result:** All 9 tests passed successfully after the fixes.

## Conclusion

Unit testing helped identify logical errors in the program. After correcting the issues, all nine tests passed, confirming that the functions behaved as expected for the tested cases.
