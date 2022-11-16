# Build Instructions

Use SSH to log in to the Perlmutter login nodes

```bash
ssh user@perlmutter-p1.nersc.gov
```

## Setup

Load the required modules

```bash
module load cmake
module load PrgEnv-gnu
```

Please make sure to copy over the data folder from the provided code harness or the repository on [Github](https://github.com/SFSU-CSC746-Fall2021/mpi_2dmesh_harness_instructional.git)

## Build and Run the Code

Build and run the code using the following commands

```bash
# Grab 4 CPU nodes
salloc --nodes 4 --qos interactive --time 01:00:00 --constraint cpu --account=m3930

# Build the program
cmake ../
make

# Run the program
bash ../scripts/run-script.sh ./mpi_2dmesh
```