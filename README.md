# Uncommon CSS `calc()` Errors and Unit Inconsistencies

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS, specifically focusing on issues related to nested elements, unit inconsistencies, and the `attr()` function.

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

**Key Issues Addressed:**

* **Nested Element Calculations:** Problems when `calc()` is used within nested elements where the parent's dimensions aren't explicitly defined.
* **Inconsistent Units:** Mixing different units (e.g., `px` and `em`) within a single `calc()` expression.
* **`attr()` Function Escaping:**  The importance of properly escaping special characters within strings passed to the `attr()` function.

This example highlights the importance of careful consideration when using `calc()` to ensure accurate and predictable layout behavior.