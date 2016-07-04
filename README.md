# levelSetCurvedBoudary

This code reconstructs a high-order mesh from a first-order STL file. Using the original triangular elements, a level set based code add interior nodes (up to sixth order) and advects these until their interpolated level set value is close to 0.

Outputs an s3d file for use in the Strand3dFC solver. 

May not work that well if the level set grid is too coarse. 

Smoothing routines may have to be applied later on to ensure a curved boundary.
