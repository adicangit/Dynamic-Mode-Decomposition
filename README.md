# Dynamic Mode Decomposition
## Fluid Flow Past a Cylinder


### DATA
Load the data set for fluid flow past a cylinder (you can download the dataset from the following link http://DMDbook.com ). The data file can be found at the following location DATA/DATA/FLUIDS/CYLINDER_ALL.mat. 

Each column is a flow field that has been reshaped into a vector. Note that you have to use the variables UALL and VALL from the dataset for [X<sub>vel</sub>] and [Y<sub>vel</sub>] velocity fields respectively. The dataset contains 151 time snapshots which is the number of columns, and each column has 199 × 449 elements where 199 corresponds to number of rows and 449 correspond to number of columns in the 2D representation of the flow fields. In the image of the flow field, considering the origin at the bottom left corner and x and y axis along the horizontal (positive towards right) and vertical directions (positive upwards) respectively, the cylinder location is present at coordinate (0.5, 1) and the diameter of the cylinder is 1 unit.

### QUESTIONS
Try to visualize the data set by reshaping a few time snapshots from the matrices [X<sub>vel</sub>] and [Y<sub>vel</sub>]. Create an animation from a series of sequential snapshots to visualize the velocities along x and y directions in the flow field.

