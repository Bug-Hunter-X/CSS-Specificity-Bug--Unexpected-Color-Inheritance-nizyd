# CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates a common CSS specificity issue that can lead to unexpected color rendering.

## The Problem

The `bug.css` file contains CSS rules that illustrate how the combination of ID and class selectors can unexpectedly override a more general rule based on the specificity rules of CSS.

## Solution

The `bugSolution.css` file presents a solution for resolving this specificity issue. In this case, we demonstrate one approach to resolve the conflict which may not always be the best approach depending on the context of your application.  It is important to be mindful of CSS specificity when writing styles to avoid unexpected behaviors.