# Uncommon HTML Bugs

This repository demonstrates two uncommon yet possible HTML bugs:

1. **Incorrect DOM Manipulation:** The code attempts to replace the content of a div without proper error handling or checking if the element actually exists, leading to potential errors.
2. **Hidden Elements and Accessibility**: A hidden div (`style.display = "none"`) is created. This hidden element and its content isn't accessible to screen readers, and can cause issues with web accessibility.