# Unexpected Layout Issues with CSS calc()

This repository demonstrates an uncommon error related to the CSS `calc()` function.  Specifically, it showcases scenarios where `calc()` interacts unexpectedly with flexbox or when unit mismatches occur.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

**Problem:** The original code uses `calc()` within a flexbox context or with mismatched units, resulting in unexpected layout behavior. 

**Solution:** The solution ensures proper unit consistency within the `calc()` expression and addresses how `calc()` might not behave predictably in all flexbox scenarios.