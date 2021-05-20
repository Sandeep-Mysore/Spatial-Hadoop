Spatial Hadoop

Domain: Big Data

Technologies & Concepts: SpatialHadoop, MapReduce, Hadoop, Spatial Data, Grid Indexing, R-tree indexing, R+tree indexing

Spatial Hadoop is a full fledge MapReduce framework with native support for spatial data. It is a comprehensive extension to Hadoop that injects spatial data awareness to each layer in Hadoop. 
The purpose of this project was to explore the use of Spatial Hadoop on Spatial Data and to evaluate and compare performances of different Spatial indexing methods on different spatial queries. The underlying intention of doing this project rose from the eagerness to explore this framework with the goal of someday being able to process Satellite data for the implementation in a real-time application.
Spatial Hadoop was installed on a Virtual Machine.
We generated rectangle datasets of various file sizes rang8ing from 100 MB to 4 GB, by using the Spatial Hadoop commands.
The generated datasets were indexed using Spatial Indexing (Grid Indexing, R-tree indexing, R+tree indexing).
We performed Spatial Range query and KNN query on the indexed files. The results were evaluated and visualized.
Grid indexing performed better than the R-tree and R+tree indexing by a magnitude of 100.
We downloaded Spatial datasets from the Spatial Hadoop websites to validate our results.
