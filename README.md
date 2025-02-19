# Unclosed Paragraph Tag in innerHTML

This repository demonstrates a subtle HTML error involving the `innerHTML` property.  Incorrectly using `innerHTML` to replace the content of a div with an unclosed paragraph tag leads to inconsistent rendering behavior across browsers. The solution shows how to avoid this issue by ensuring that all HTML tags are properly closed.

## Bug
The `bug.html` file shows the error.  The script replaces the div's content with an HTML string containing an unclosed paragraph tag. This causes the browser to attempt to recover, often leading to unexpected layout or display issues.

## Solution
The `solution.html` file demonstrates the correct way to use `innerHTML`.  The replacement string is valid HTML with properly closed tags, ensuring consistent and predictable rendering.