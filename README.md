# Uncommon HTML Bug: Incorrect <details> and <summary> Nesting

This repository demonstrates a subtle but important error related to the use of the HTML `<details>` and `<summary>` elements.  The problem arises when the nesting order of these elements is incorrect, leading to unexpected display behavior.

## The Bug

The bug is demonstrated in `bug.html`.  Observe that the second `<details>` element fails to function as expected.  The content inside is not hidden initially and the `<summary>` element is not effective.

## The Solution

The correct usage is shown in `bugSolution.html`. The `<summary>` element *must* be the first child element of the `<details>` element.  Only then will the `<details>` element work as intended.

## Learning Points

This example highlights the importance of correct HTML tag nesting.  Even seemingly minor deviations from proper structure can result in unexpected behavior.