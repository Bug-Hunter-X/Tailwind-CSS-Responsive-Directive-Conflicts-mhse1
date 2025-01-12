# Tailwind CSS Responsive Directive Conflicts

This repository demonstrates a bug related to conflicting responsive directives in Tailwind CSS. The bug manifests when multiple responsive utility classes are applied to the same element, causing unexpected behavior in terms of style application and transitions.

## Bug Description
The core issue lies in the way Tailwind CSS handles overlapping responsive directives.  When multiple directives apply to the same style (e.g., background color), the order or prioritization might not be intuitive, leading to styles not being applied as intended. This often leads to subtle visual errors that are difficult to debug.

## Steps to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the styles do not behave as expected due to conflicting responsive directives.
4. Compare it to `bugSolution.html` to see the corrected behavior.

## Solution
The provided solution illustrates a method for resolving the conflicts, often involving careful consideration of the order of directives or the use of more specific classes to ensure the expected behavior.

## Technologies Used
* Tailwind CSS
* HTML