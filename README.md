GIS-in-R
========
Basic GIS Functions include:
	Transformation  (Adriano; Simon K)
	Reproject       (Adriano; Simon K)
	Buffer, Clip, Merge, Intersect, Dissolve, Extract, ect. (Adriano; Simon K)
	Raster calculator (Katha; Simon S)
	Proximity Analysis and other Geostatistics (Simon K; Adriano)
	Maps, Maps, Maps (Katha; Simon S)
	Traveling Salesman Problematic
	edit Topology
	join and relate tables
	create mosaics
	

possible strugles include...:
	Classifications (supervised and unsupervised)
	3D Data


Can we...
... build shapes in R? (other than Points and Poly-Lines) (Katha; Simon S)
... design Geodatabses?
... construct workflows for specific tasks?
... create output readable in Arc- or QGIS?

Usefuls URLs:
http://shiny.rstudio.com/articles/rmarkdown.html (explains basic markdown functions)


Usable Packages:

Package ‘PBSmapping’:
This software has evolved from fisheries research conducted at the
Pacific Biological Station (PBS) in Nanaimo, British Columbia, Canada. It
extends the R language to include two-dimensional plotting features similar
to those commonly available in a Geographic Information System (GIS).
Embedded C code speeds algorithms from computational geometry, such as
finding polygons that contain specified point events or converting between
longitude-latitude and Universal Transverse Mercator (UTM) coordinates.
Additionally, we include C++ code developed by Angus Johnson for the Clipper
library. PBSmapping also includes data for a global shoreline and other
data sets in the public domain.
The R directory '.../library/PBSmapping/doc' offers a complete user's
guide PBSmapping-UG.pdf, which should be consulted to use all functions in
the package effectively.

Package ‘raster’:
Reading, writing, manipulating, analyzing and modeling of gridded spatial data. The pack-
age implements basic and high-level functions. Processing of very large files is supported

Package ‘adehabitat:
The package adehabitat has been designed to allow the analysis of the space use by animals.
This package is organised in four main parts: (i) management of raster maps, (ii) habitat selec-
tion/ecological niche analysis, (iii) home range estimation and (iv) analysis of animals trajectories.
These four parts interact with each other to facilitate the analysis. Note that adehabitat strongly
relies on the package ade4, which provides numerous functions for the analysis of multivariate
data





