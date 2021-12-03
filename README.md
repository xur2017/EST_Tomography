# EST_Tomography
Tomography has made revolutionary impacts in a number of fields ranging from medical imaging to electron microscopy.
Conventional tomography reconstructs a 3D object from a set of equal-angle 2D projections.
Since the set of projections are in polar coordinates and the object in Cartesian coordinates,
interpolation has to be used in the reconstruction process,
which introduces artifacts in the reconstructed 3D object.

When the projections of a tilt series use equal slope increments,
it has been shown that a direct fast Fourier transform,
the PPFFT, exists between a pseudopolar grid and a Cartesian grid. For an N * N Cartesian grid,
the corresponding pseudopolar grid is defined by a set of 2N lines,
each line consisting of 2N grid points mapped out on N concentric squares.
The 2N lines are subdivided into a horizontal group defined by y = sx,
where s is the slope and |s|<=1,
and a vertical group defined by x = sy, where |s|<=1.
The horizontal and vertical groups are symmetric under the interchange of x and y, and s = 2/N.
When these conditions are met, the PPFFT and its inverse algorithm are mathematically faithful.

Compared to other data acquisition approaches such as the Saxton scheme,
the EST data acquisition approach is different in that it acquires projections with equal slope increments in order to use the PPFFT. 
