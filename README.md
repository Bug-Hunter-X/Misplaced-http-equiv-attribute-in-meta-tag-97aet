# Misplaced http-equiv Attribute in Meta Tag

This repository demonstrates a subtle and uncommon HTML bug involving the placement of the `http-equiv` attribute in a meta tag. The issue is that the attribute is incorrectly placed outside the tag, leading to unexpected behavior in some browsers.

## Bug Description
The bug occurs when the `http-equiv` attribute is added after the `charset` attribute.  The correct syntax should have both attributes placed within the opening meta tag.

## Bug Solution
The solution involves correctly placing the `http-equiv` attribute within the meta tag, ensuring that the attributes are set within the tag itself.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser. Observe that the meta tag might render inconsistently in some browsers.
3. Open `bugSolution.html` and observe the corrected code for comparison.