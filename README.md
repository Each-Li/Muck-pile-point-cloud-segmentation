MPPCS:A lightweight muck pile point cloud segmentation tool
MPPCS is a C++-based point cloud segmentation tool designed for instance segmentation of discrete 3D laser point clouds of blast heaps. The code has been tested on the Windows operating system. Before using the segmentation tool, users need to preprocess the data to extract the necessary features and align the organizational structure of the data.
First, import the point cloud data in XYZ format into the "01 Calculate curvature point cloud density" code block.
Then, input the resulting file sequentially into "02 Curvature principal component analysis and outlier removal" and "03 Extract contextual features."
Finally, import the output .txt file into the main program and adjust the parameters as needed.
