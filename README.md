# Parallelization-of-PSO
Paralleling  Particle Swarm Optimization using OpenMp, MPI and CUDA frameworks and comparing the performance
command to run omp.c    : gcc -fopenmp omp.c pkg-config --cflags --libs gsl 
command to run mpiomp.c : mpicc -fopenmp mpiomp.c pkg-config --cflags --libs gsl
