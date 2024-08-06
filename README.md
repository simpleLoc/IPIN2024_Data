Repository containing data and animation plots of the filter runs used in the evaluation of the paper at IPIN 2024 with the title: "Refinement of Sparsely Tagged Ground Truth Paths Using PDR and Particle Filter Smoothing"

Naming of trajectory files:
- Path0_10_FO.html: Path 0 using every 10th GT and method forward-only
- Path0_15_FB.html: Path 0 using every 15th GT and method forward-backward
- Path0_30_OF.html: Path 0 using every 30th GT and method optimal-forward

Plots are made using [Plotly](https://plotly.com/python/).

The data was recorded using the [SensorReadoutApp](https://github.com/simpleLoc/SensorReadoutApp).

The `building.xml` file contains a map of the building which can be parsed using the [IndoorMapParser](https://github.com/simpleLoc/IndoorMapParser).
Using the `building.xml` file we create a boundary mesh that constraints our particle movement. I additionally exported this mesh to `building.obj` for easier access.

The recordings used for the evaluation can be found in the `Recordings with Sparse Tagging` directory.
The result runs of `Table I` can be found in the `Particle Amount Plots` directory.
The result runs of `Table II` can be found in the `Ground Truth Sparsity` directory.
