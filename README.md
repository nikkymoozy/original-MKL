# R13 moment equaitons for the non-equilibrium fluid flows

Originally develped by Prof. Dr. Manuel Torrilhon. Here, the performance of several linear solvers for this implementation has been tested by Mohsen Sadr.  

You should be able to compile with '$make MKL' for MKL pardiso and '$make original' for the original pardiso. I know that the Makefile can be cleaner but I am changing things too often. The setting_path.sh is meant for setting the paths, nothing fancy. Please note that recent versions of -lgfortran is required by original pardiso that I had to install. 

Changes are made in Makefile, EigenSetup.h, Numerics.cpp and pardisoSolve_GNU_Original.cpp is added.
