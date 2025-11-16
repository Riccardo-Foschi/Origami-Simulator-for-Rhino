OrigamiSIM for Grasshopper is a single Algorithm aimed at simulating the folding and unfolding of Origami Crease Patterns (CP).

The Crease patterns are drawn in Rhino as Curves and uploaded to Grasshopper.

It supports the following types of CP curves:
-mountain
-valley
-unassigned
-boundaries

Also, it supports several constraints:
-Attractor/Anchor points
-Glue points
-Points sliding on curve rails
-Points sliding on surfaces
-Planarization of curves
-Elastic wires

It supports mesh generation from curves and points based on Constrained Delaunay triangulation (CDT)

It includes analysis tools:
-estimation of approximated ruling (for curve folded designs)
-estimation of area and length error
-colorization of the mesh based on error

Once the CP is folded, the final discretized mesh can be baked into Rhino
