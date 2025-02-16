# Floating-Point Comparison Issues in Julia

This repository demonstrates a common pitfall in Julia programming involving floating-point number comparisons.  The `bug.jl` file contains code that exhibits unexpected behavior due to the inherent limitations of floating-point representation.

The solution (`bugSolution.jl`) showcases how to mitigate this problem by using tolerances or alternative comparison methods.