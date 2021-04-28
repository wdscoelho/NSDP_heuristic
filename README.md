In this work, we address the Network Slice Design problem. This is a problem arising from the optimization of end-to-end communication networks using fifth-generation (5G) radio access technology showing peculiar requirements with respect to conventional function placement and routing problems, in terms of sharing policies and radio-access integration. To address the underlying optimization problem, we propose an open-access framework based on a math-heuristic that encompasses control-plane and data-plane separation and novel mapping and decomposition dimensions influencing the placement and interconnection of slices. Our framework also incorporates flexible functional splitting, with possibly different splitting for different slices while taking into consideration dependency factors such as varying network latency and data volume throughout the virtual access networks. Numerical results are then presented to assess the efficiency of our approach. 

The code-source is written in Julia-JuMP language for Jupyter environment. You will find below the version of each library used in this work.

JULIA v1.2.0

CPLEX v0.7.0

DataStructures v0.17.0

Distributions v0.23.0

GraphIO v0.4.0

GraphPlot v0.3.1

Graphs v0.10.3

IJulia v1.20.0

JuMP v0.21

LightGraphs v1.3.0

LightGraphsFlows v0.3.1

MathProgBase v0.7.7

MetaGraphs v0.6.4

NBInclude v2.1.0

ParserCombinator v2.0.0
