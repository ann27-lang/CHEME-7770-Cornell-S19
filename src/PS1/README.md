### PS1 Solution
To execute the problem set 1 solution, start the Julia REPL and run the command:

    julia> include("PS1-solution.jl")

The solution script will produce two PDF plots, mRNA versus Inducer I and u versus inducer I.
The solution scripts requires the following packages (installed using the ``Pkg`` tools or ``pip``):

Package | Description
--- | ---
numpy | NumPy package in Python
PyPlot | Julia wrapper around Matplotlib
PyCall | Julia python bridge
DelimitedFiles | Package the reads/writes delimited text files
