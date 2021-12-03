# EST_Tomography

When the projections of a tilt series use equal slope increments,
it has been shown that a direct fast Fourier transform,
the PPFFT, exists between a pseudopolar grid and a Cartesian grid. For an N * N Cartesian grid,
the corresponding pseudopolar grid is defined by a set of 2N lines,
each line consisting of 2N grid points mapped out on N concentric squares.
The 2N lines are subdivided into a horizontal group (in blue) defined by y = sx,
where s is the slope and |s|<=1,
and a vertical group (in red) defined by x = sy, where |s|<=1;
the horizontal and vertical groups are symmetric under the interchange of x and y, and s = 2/N.
When these conditions are met, the PPFFT and its inverse algorithm are mathematically faithful.
