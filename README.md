# Hidden HTML Element Bug

This repository demonstrates a common yet easily overlooked error in HTML/JavaScript: hiding an element without providing a mechanism to restore its visibility.  The `bug.html` file shows the issue; the element disappears after clicking the button and never returns.  `solution.html` provides the corrected code.

## Bug Description
The JavaScript function hides the div element using `style.display = "none";` but doesn't include any code to reverse this action. This leads to the content becoming permanently hidden.

## Solution
The solution adds a timeout or an alternative method to show the element after a delay or under certain conditions to fix the issue.