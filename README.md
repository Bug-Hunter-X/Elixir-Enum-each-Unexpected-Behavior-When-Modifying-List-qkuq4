# Elixir Enum.each List Modification Bug

This example demonstrates a common misconception when using `Enum.each` in Elixir to modify a list during iteration.  The code attempts to remove the element `3` from the list, but it fails to do so because `Enum.each` does not alter the list directly.  The correct approach involves using other functions like `Enum.filter` or `Enum.reduce` for in-place list manipulations.

The solution demonstrates how to achieve the desired result using `Enum.filter`.