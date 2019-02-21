## PS2 Solution
To execute the problem set 2 solution, start the Julia REPL and run the command:

    julia> include("Q*.jl")

where ``*`` = 2 or 3 (the solution for the sensitivity problem is still under development).
The ``Q*.jl`` scripts produce a plot of ``P*`` versus time for the default or broken network.
To simulate the broken network case, change the ``simulation_case_flag`` at the top of the
script to:

  ``jl
    simulation_case_flag = :broken
  ``
(or back to ``:default`` for the default circuit). 

### Requirements
To execute the solution scripts you need to have the ``GRNSimKit`` package installed. ``GRNSimKit`` uses a ``JSON`` formatted model schematic to structure the gene regulatory model, and provides several methods to solve the model equations. See the
``GRNSimKit`` [documentation](https://varnerlab.github.io/GRNSimKit/) for details.
