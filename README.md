# Tailwind CSS Arbitrary Value Gradient Bug

This repository demonstrates an uncommon bug encountered when using arbitrary values with Tailwind CSS gradient backgrounds. The gradient might not render as expected, displaying unexpected colors or no gradient at all.

## Bug Description

The issue arises when using arbitrary values (like hex codes or rgb values) in place of standard Tailwind color classes within the `from-` and `to-` directives of gradient backgrounds.  The result may be an unexpected or incorrect gradient, or a complete failure to render the gradient.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`. This file demonstrates the code that causes the issue.
3. Build and run the project. Observe the incorrect gradient in the output. 

## Solution

The `bugSolution.js` file presents a workaround using named colors or pre-defined Tailwind color classes. This solution ensures that the gradient renders correctly, eliminating the unexpected behaviour.

## Additional Notes

This bug might be related to specific versions of Tailwind CSS or interactions with other CSS frameworks or libraries.  Always refer to the official Tailwind documentation for best practices and solutions to emerging issues. 
