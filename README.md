# CSS Calc() Function Unexpected Behavior

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The bug arises from unexpected behavior and calculation order inconsistencies, particularly when dealing with nested calculations and dependencies on dynamically-calculated element dimensions.

## Bug Description

The `calc()` function is powerful, but it can lead to unexpected results if not used carefully. This example showcases a scenario where the calculated width of an element differs from the expected value, possibly due to rounding errors or the order in which the browser evaluates the different parts of the calculation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the code that produces the unexpected behavior.
3. Open `bugSolution.css` to see a possible solution.
4. Use the CSS in your project to observe the unexpected output and then the fixed output.

## Solution

The solution might involve restructuring the CSS calculations, using intermediate variables to control the calculation order, or applying workarounds based on specific browser behavior.  See `bugSolution.css` for a demonstration.