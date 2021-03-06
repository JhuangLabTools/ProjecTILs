# ProjecTILs - Functions

* `load.reference.map`   Load or download the reference map for dataset projection. By the default it downloads the reference atlas of tumour-infiltrating lymphocytes (TILs).

* `make.projection`   Project a single-cell RNA-seq dataset onto a reference map of cellular states.

* `plot.projection`   Plots the UMAP representation of the reference map, together with the projected coordinates of a query dataset.

* `cellstate.predict`   Use a nearest-neighbor algorithm to predict a feature (e.g. the cell state) of the query cells.

* `plot.statepred.composition`   Makes a barplot of the frequency of cell states in a query object.

* `plot.states.radar`   Makes a radar plot of the expression level of a specified set of genes.

* `find.discriminant.dimensions`   Searches PCA or ICA dimensions where the query set deviates the most from a control set or from the reference map.


* `plot.discriminant.3d`   Add an extra dimension to the reference map  to explore additional axes of variability in a query dataset compared to the reference map.

Find more information, syntax and examples using the R help function e.g. `?make.projection`

