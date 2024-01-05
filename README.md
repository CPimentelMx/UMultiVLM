# o-UMultiVLM
The Unsteady Full Multi-wake Vortex Lattice Method (UFVLM; "original" version: only for multi-wake dynamics verification).

Fortran (Visual Studio Project)

1. You should have installed Visual Studio 2017 (or higher version with Fortran compiler) and "GiD" (pre and post-processor; www.gidsimulation.com).
2. Open UMultiVLM.vfproj
3. Go to input.txt (optional to change parameters).
4. Press "start" to run the code (and wait for it to finish).
5. To visualize the results (multi-wake dynamics) change to post-processor mode in GiD and open/drag the .msh file.
6. Enjoy the spiderwebs!

Note: The new version (v1.1; Jan/2024) includes a 4x13 mesh (AR = 4); besides, parameter "lambda" has been renamed as "low_phi" (lowercase phi) to maintain consistency with the most recent manuscript version.
