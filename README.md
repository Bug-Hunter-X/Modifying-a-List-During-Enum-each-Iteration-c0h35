# Elixir List Modification During Enum.each

This example demonstrates a common mistake in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The code intends to remove the element `3` from the list, but due to immutability, this will not work as expected.

The provided `bug.exs` file contains the erroneous code, and `bugSolution.exs` offers a corrected approach.

## How to Reproduce

1. Save the code in `bug.exs`.
2. Run the code using `elixir bug.exs`.
3. Observe that the list remains unchanged despite the attempt to remove the element.