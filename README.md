# Uncommon HTML innerHTML Bug

This repository demonstrates a subtle bug related to manipulating the `innerHTML` property of an HTML element. The incorrect approach can lead to unexpected behavior and reduced performance.  The correct method is also shown for comparison.

## Bug Description
The primary issue lies in how the `innerHTML` property is accessed and modified.  The original code attempts to directly modify the property by assigning it a new value based on its current value which is slightly inefficient. The solution shows the correct approach for better efficiency.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected behavior.
4. Compare with the corrected code in `bugSolution.html`.