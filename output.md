# RAW Output

```bash
 bash ../scripts/run_script.sh ./mpi_2dmesh
 srun -n 4 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 3 of 4 total ranks running on <nid004935>
Hello world, I'm rank 1 of 4 total ranks running on <nid004933>
Hello world, I'm rank 2 of 4 total ranks running on <nid004934>
Hello world, I'm rank 0 of 4 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	30.8568 (ms) 
	Sobel time:	44.7325 (ms) 
	Gather time:	13.2582 (ms) 
 srun -n 4 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 2 of 4 total ranks running on <nid004934>
Hello world, I'm rank 3 of 4 total ranks running on <nid004935>
Hello world, I'm rank 1 of 4 total ranks running on <nid004933>
Hello world, I'm rank 0 of 4 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	53.1505 (ms) 
	Sobel time:	44.1098 (ms) 
	Gather time:	50.1327 (ms) 
 srun -n 4 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 1 of 4 total ranks running on <nid004933>
Hello world, I'm rank 2 of 4 total ranks running on <nid004934>
Hello world, I'm rank 3 of 4 total ranks running on <nid004935>
Hello world, I'm rank 0 of 4 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	49.5776 (ms) 
	Sobel time:	43.9379 (ms) 
	Gather time:	39.7531 (ms) 
 srun -n 9 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 1 of 9 total ranks running on <nid004932>
Hello world, I'm rank 5 of 9 total ranks running on <nid004934>
Hello world, I'm rank 7 of 9 total ranks running on <nid004935>
Hello world, I'm rank 4 of 9 total ranks running on <nid004933>
Hello world, I'm rank 6 of 9 total ranks running on <nid004934>
Hello world, I'm rank 2 of 9 total ranks running on <nid004932>
Hello world, I'm rank 8 of 9 total ranks running on <nid004935>
Hello world, I'm rank 3 of 9 total ranks running on <nid004933>
Hello world, I'm rank 0 of 9 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	38.4823 (ms) 
	Sobel time:	20.2026 (ms) 
	Gather time:	30.7984 (ms) 
 srun -n 9 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 1 of 9 total ranks running on <nid004932>
Hello world, I'm rank 6 of 9 total ranks running on <nid004934>
Hello world, I'm rank 8 of 9 total ranks running on <nid004935>
Hello world, I'm rank 3 of 9 total ranks running on <nid004933>
Hello world, I'm rank 2 of 9 total ranks running on <nid004932>
Hello world, I'm rank 7 of 9 total ranks running on <nid004935>
Hello world, I'm rank 4 of 9 total ranks running on <nid004933>
Hello world, I'm rank 5 of 9 total ranks running on <nid004934>
Hello world, I'm rank 0 of 9 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	58.1553 (ms) 
	Sobel time:	20.2183 (ms) 
	Gather time:	34.9774 (ms) 
 srun -n 9 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 1 of 9 total ranks running on <nid004932>
Hello world, I'm rank 2 of 9 total ranks running on <nid004932>
Hello world, I'm rank 7 of 9 total ranks running on <nid004935>
Hello world, I'm rank 6 of 9 total ranks running on <nid004934>
Hello world, I'm rank 4 of 9 total ranks running on <nid004933>
Hello world, I'm rank 5 of 9 total ranks running on <nid004934>
Hello world, I'm rank 8 of 9 total ranks running on <nid004935>
Hello world, I'm rank 3 of 9 total ranks running on <nid004933>
Hello world, I'm rank 0 of 9 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	64.8510 (ms) 
	Sobel time:	20.3686 (ms) 
	Gather time:	48.3352 (ms) 
 srun -n 16 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 10 of 16 total ranks running on <nid004934>
Hello world, I'm rank 3 of 16 total ranks running on <nid004932>
Hello world, I'm rank 1 of 16 total ranks running on <nid004932>
Hello world, I'm rank 8 of 16 total ranks running on <nid004934>
Hello world, I'm rank 7 of 16 total ranks running on <nid004933>
Hello world, I'm rank 2 of 16 total ranks running on <nid004932>
Hello world, I'm rank 5 of 16 total ranks running on <nid004933>
Hello world, I'm rank 9 of 16 total ranks running on <nid004934>
Hello world, I'm rank 15 of 16 total ranks running on <nid004935>
Hello world, I'm rank 13 of 16 total ranks running on <nid004935>
Hello world, I'm rank 4 of 16 total ranks running on <nid004933>
Hello world, I'm rank 14 of 16 total ranks running on <nid004935>
Hello world, I'm rank 6 of 16 total ranks running on <nid004933>
Hello world, I'm rank 11 of 16 total ranks running on <nid004934>
Hello world, I'm rank 12 of 16 total ranks running on <nid004935>
Hello world, I'm rank 0 of 16 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	42.9545 (ms) 
	Sobel time:	11.3122 (ms) 
	Gather time:	31.6712 (ms) 
 srun -n 16 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 5 of 16 total ranks running on <nid004933>
Hello world, I'm rank 14 of 16 total ranks running on <nid004935>
Hello world, I'm rank 9 of 16 total ranks running on <nid004934>
Hello world, I'm rank 15 of 16 total ranks running on <nid004935>
Hello world, I'm rank 7 of 16 total ranks running on <nid004933>
Hello world, I'm rank 2 of 16 total ranks running on <nid004932>
Hello world, I'm rank 4 of 16 total ranks running on <nid004933>
Hello world, I'm rank 8 of 16 total ranks running on <nid004934>
Hello world, I'm rank 3 of 16 total ranks running on <nid004932>
Hello world, I'm rank 11 of 16 total ranks running on <nid004934>
Hello world, I'm rank 6 of 16 total ranks running on <nid004933>
Hello world, I'm rank 13 of 16 total ranks running on <nid004935>
Hello world, I'm rank 1 of 16 total ranks running on <nid004932>
Hello world, I'm rank 12 of 16 total ranks running on <nid004935>
Hello world, I'm rank 0 of 16 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	72.9921 (ms) 
	Sobel time:	11.3679 (ms) 
	Gather time:	43.0118 (ms) 
Hello world, I'm rank 10 of 16 total ranks running on <nid004934>
 srun -n 16 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 5 of 16 total ranks running on <nid004933>
Hello world, I'm rank 3 of 16 total ranks running on <nid004932>
Hello world, I'm rank 1 of 16 total ranks running on <nid004932>
Hello world, I'm rank 2 of 16 total ranks running on <nid004932>
Hello world, I'm rank 15 of 16 total ranks running on <nid004935>
Hello world, I'm rank 6 of 16 total ranks running on <nid004933>
Hello world, I'm rank 7 of 16 total ranks running on <nid004933>
Hello world, I'm rank 13 of 16 total ranks running on <nid004935>
Hello world, I'm rank 12 of 16 total ranks running on <nid004935>
Hello world, I'm rank 4 of 16 total ranks running on <nid004933>
Hello world, I'm rank 0 of 16 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	60.4995 (ms) 
	Sobel time:	11.2880 (ms) 
	Gather time:	34.5641 (ms) 
Hello world, I'm rank 9 of 16 total ranks running on <nid004934>
Hello world, I'm rank 8 of 16 total ranks running on <nid004934>
Hello world, I'm rank 10 of 16 total ranks running on <nid004934>
Hello world, I'm rank 11 of 16 total ranks running on <nid004934>
Hello world, I'm rank 14 of 16 total ranks running on <nid004935>
 srun -n 25 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 15 of 25 total ranks running on <nid004934>
Hello world, I'm rank 3 of 25 total ranks running on <nid004932>
Hello world, I'm rank 23 of 25 total ranks running on <nid004935>
Hello world, I'm rank 14 of 25 total ranks running on <nid004934>
Hello world, I'm rank 8 of 25 total ranks running on <nid004933>
Hello world, I'm rank 22 of 25 total ranks running on <nid004935>
Hello world, I'm rank 10 of 25 total ranks running on <nid004933>
Hello world, I'm rank 17 of 25 total ranks running on <nid004934>
Hello world, I'm rank 21 of 25 total ranks running on <nid004935>
Hello world, I'm rank 13 of 25 total ranks running on <nid004934>
Hello world, I'm rank 4 of 25 total ranks running on <nid004932>
Hello world, I'm rank 24 of 25 total ranks running on <nid004935>
Hello world, I'm rank 6 of 25 total ranks running on <nid004932>
Hello world, I'm rank 1 of 25 total ranks running on <nid004932>
Hello world, I'm rank 5 of 25 total ranks running on <nid004932>
Hello world, I'm rank 16 of 25 total ranks running on <nid004934>
Hello world, I'm rank 11 of 25 total ranks running on <nid004933>
Hello world, I'm rank 9 of 25 total ranks running on <nid004933>
Hello world, I'm rank 20 of 25 total ranks running on <nid004935>
Hello world, I'm rank 2 of 25 total ranks running on <nid004932>
Hello world, I'm rank 18 of 25 total ranks running on <nid004934>
Hello world, I'm rank 19 of 25 total ranks running on <nid004935>
Hello world, I'm rank 7 of 25 total ranks running on <nid004933>
Hello world, I'm rank 0 of 25 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	42.0561 (ms) 
	Sobel time:	9.3117 (ms) 
	Gather time:	32.5806 (ms) 
Hello world, I'm rank 12 of 25 total ranks running on <nid004933>
 srun -n 25 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 16 of 25 total ranks running on <nid004934>
Hello world, I'm rank 7 of 25 total ranks running on <nid004933>
Hello world, I'm rank 21 of 25 total ranks running on <nid004935>
Hello world, I'm rank 1 of 25 total ranks running on <nid004932>
Hello world, I'm rank 4 of 25 total ranks running on <nid004932>
Hello world, I'm rank 23 of 25 total ranks running on <nid004935>
Hello world, I'm rank 8 of 25 total ranks running on <nid004933>
Hello world, I'm rank 17 of 25 total ranks running on <nid004934>
Hello world, I'm rank 15 of 25 total ranks running on <nid004934>
Hello world, I'm rank 24 of 25 total ranks running on <nid004935>
Hello world, I'm rank 9 of 25 total ranks running on <nid004933>
Hello world, I'm rank 11 of 25 total ranks running on <nid004933>
Hello world, I'm rank 18 of 25 total ranks running on <nid004934>
Hello world, I'm rank 13 of 25 total ranks running on <nid004934>
Hello world, I'm rank 5 of 25 total ranks running on <nid004932>
Hello world, I'm rank 3 of 25 total ranks running on <nid004932>
Hello world, I'm rank 6 of 25 total ranks running on <nid004932>
Hello world, I'm rank 2 of 25 total ranks running on <nid004932>
Hello world, I'm rank 14 of 25 total ranks running on <nid004934>
Hello world, I'm rank 20 of 25 total ranks running on <nid004935>
Hello world, I'm rank 22 of 25 total ranks running on <nid004935>
Hello world, I'm rank 10 of 25 total ranks running on <nid004933>
Hello world, I'm rank 19 of 25 total ranks running on <nid004935>
Hello world, I'm rank 0 of 25 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	78.4407 (ms) 
	Sobel time:	7.6651 (ms) 
	Gather time:	61.4829 (ms) 
Hello world, I'm rank 12 of 25 total ranks running on <nid004933>
 srun -n 25 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 15 of 25 total ranks running on <nid004934>
Hello world, I'm rank 2 of 25 total ranks running on <nid004932>
Hello world, I'm rank 5 of 25 total ranks running on <nid004932>
Hello world, I'm rank 9 of 25 total ranks running on <nid004933>
Hello world, I'm rank 7 of 25 total ranks running on <nid004933>
Hello world, I'm rank 10 of 25 total ranks running on <nid004933>
Hello world, I'm rank 1 of 25 total ranks running on <nid004932>
Hello world, I'm rank 11 of 25 total ranks running on <nid004933>
Hello world, I'm rank 17 of 25 total ranks running on <nid004934>
Hello world, I'm rank 3 of 25 total ranks running on <nid004932>
Hello world, I'm rank 8 of 25 total ranks running on <nid004933>
Hello world, I'm rank 16 of 25 total ranks running on <nid004934>
Hello world, I'm rank 6 of 25 total ranks running on <nid004932>
Hello world, I'm rank 4 of 25 total ranks running on <nid004932>
Hello world, I'm rank 23 of 25 total ranks running on <nid004935>
Hello world, I'm rank 18 of 25 total ranks running on <nid004934>
Hello world, I'm rank 12 of 25 total ranks running on <nid004933>
Hello world, I'm rank 19 of 25 total ranks running on <nid004935>
Hello world, I'm rank 22 of 25 total ranks running on <nid004935>
Hello world, I'm rank 24 of 25 total ranks running on <nid004935>
Hello world, I'm rank 0 of 25 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	71.7598 (ms) 
	Sobel time:	7.2442 (ms) 
	Gather time:	51.9005 (ms) 
Hello world, I'm rank 20 of 25 total ranks running on <nid004935>
Hello world, I'm rank 13 of 25 total ranks running on <nid004934>
Hello world, I'm rank 14 of 25 total ranks running on <nid004934>
Hello world, I'm rank 21 of 25 total ranks running on <nid004935>
 srun -n 36 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 10 of 36 total ranks running on <nid004933>
Hello world, I'm rank 28 of 36 total ranks running on <nid004935>
Hello world, I'm rank 20 of 36 total ranks running on <nid004934>
Hello world, I'm rank 17 of 36 total ranks running on <nid004933>
Hello world, I'm rank 16 of 36 total ranks running on <nid004933>
Hello world, I'm rank 4 of 36 total ranks running on <nid004932>
Hello world, I'm rank 30 of 36 total ranks running on <nid004935>
Hello world, I'm rank 14 of 36 total ranks running on <nid004933>
Hello world, I'm rank 27 of 36 total ranks running on <nid004935>
Hello world, I'm rank 2 of 36 total ranks running on <nid004932>
Hello world, I'm rank 31 of 36 total ranks running on <nid004935>
Hello world, I'm rank 11 of 36 total ranks running on <nid004933>
Hello world, I'm rank 35 of 36 total ranks running on <nid004935>
Hello world, I'm rank 33 of 36 total ranks running on <nid004935>
Hello world, I'm rank 34 of 36 total ranks running on <nid004935>
Hello world, I'm rank 6 of 36 total ranks running on <nid004932>
Hello world, I'm rank 15 of 36 total ranks running on <nid004933>
Hello world, I'm rank 9 of 36 total ranks running on <nid004933>
Hello world, I'm rank 22 of 36 total ranks running on <nid004934>
Hello world, I'm rank 12 of 36 total ranks running on <nid004933>
Hello world, I'm rank 26 of 36 total ranks running on <nid004934>
Hello world, I'm rank 8 of 36 total ranks running on <nid004932>
Hello world, I'm rank 32 of 36 total ranks running on <nid004935>
Hello world, I'm rank 13 of 36 total ranks running on <nid004933>
Hello world, I'm rank 19 of 36 total ranks running on <nid004934>
Hello world, I'm rank 3 of 36 total ranks running on <nid004932>
Hello world, I'm rank 1 of 36 total ranks running on <nid004932>
Hello world, I'm rank 5 of 36 total ranks running on <nid004932>
Hello world, I'm rank 29 of 36 total ranks running on <nid004935>
Hello world, I'm rank 7 of 36 total ranks running on <nid004932>
Hello world, I'm rank 21 of 36 total ranks running on <nid004934>
Hello world, I'm rank 25 of 36 total ranks running on <nid004934>
Hello world, I'm rank 23 of 36 total ranks running on <nid004934>
Hello world, I'm rank 24 of 36 total ranks running on <nid004934>
Hello world, I'm rank 0 of 36 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	47.1959 (ms) 
	Sobel time:	6.0231 (ms) 
	Gather time:	32.2470 (ms) 
Hello world, I'm rank 18 of 36 total ranks running on <nid004934>
 srun -n 36 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 20 of 36 total ranks running on <nid004934>
Hello world, I'm rank 23 of 36 total ranks running on <nid004934>
Hello world, I'm rank 3 of 36 total ranks running on <nid004932>
Hello world, I'm rank 6 of 36 total ranks running on <nid004932>
Hello world, I'm rank 22 of 36 total ranks running on <nid004934>
Hello world, I'm rank 26 of 36 total ranks running on <nid004934>
Hello world, I'm rank 14 of 36 total ranks running on <nid004933>
Hello world, I'm rank 1 of 36 total ranks running on <nid004932>
Hello world, I'm rank 2 of 36 total ranks running on <nid004932>
Hello world, I'm rank 10 of 36 total ranks running on <nid004933>
Hello world, I'm rank 21 of 36 total ranks running on <nid004934>
Hello world, I'm rank 18 of 36 total ranks running on <nid004934>
Hello world, I'm rank 17 of 36 total ranks running on <nid004933>
Hello world, I'm rank 7 of 36 total ranks running on <nid004932>
Hello world, I'm rank 8 of 36 total ranks running on <nid004932>
Hello world, I'm rank 16 of 36 total ranks running on <nid004933>
Hello world, I'm rank 24 of 36 total ranks running on <nid004934>
Hello world, I'm rank 25 of 36 total ranks running on <nid004934>
Hello world, I'm rank 5 of 36 total ranks running on <nid004932>
Hello world, I'm rank 0 of 36 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	69.8799 (ms) 
	Sobel time:	5.8695 (ms) 
	Gather time:	61.6820 (ms) 
Hello world, I'm rank 12 of 36 total ranks running on <nid004933>
Hello world, I'm rank 30 of 36 total ranks running on <nid004935>
Hello world, I'm rank 27 of 36 total ranks running on <nid004935>
Hello world, I'm rank 29 of 36 total ranks running on <nid004935>
Hello world, I'm rank 11 of 36 total ranks running on <nid004933>
Hello world, I'm rank 13 of 36 total ranks running on <nid004933>
Hello world, I'm rank 32 of 36 total ranks running on <nid004935>
Hello world, I'm rank 28 of 36 total ranks running on <nid004935>
Hello world, I'm rank 31 of 36 total ranks running on <nid004935>
Hello world, I'm rank 4 of 36 total ranks running on <nid004932>
Hello world, I'm rank 15 of 36 total ranks running on <nid004933>
Hello world, I'm rank 33 of 36 total ranks running on <nid004935>
Hello world, I'm rank 34 of 36 total ranks running on <nid004935>
Hello world, I'm rank 19 of 36 total ranks running on <nid004934>
Hello world, I'm rank 35 of 36 total ranks running on <nid004935>
Hello world, I'm rank 9 of 36 total ranks running on <nid004933>
 srun -n 36 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 11 of 36 total ranks running on <nid004933>
Hello world, I'm rank 19 of 36 total ranks running on <nid004934>
Hello world, I'm rank 15 of 36 total ranks running on <nid004933>
Hello world, I'm rank 12 of 36 total ranks running on <nid004933>
Hello world, I'm rank 26 of 36 total ranks running on <nid004934>
Hello world, I'm rank 22 of 36 total ranks running on <nid004934>
Hello world, I'm rank 10 of 36 total ranks running on <nid004933>
Hello world, I'm rank 34 of 36 total ranks running on <nid004935>
Hello world, I'm rank 29 of 36 total ranks running on <nid004935>
Hello world, I'm rank 30 of 36 total ranks running on <nid004935>
Hello world, I'm rank 33 of 36 total ranks running on <nid004935>
Hello world, I'm rank 13 of 36 total ranks running on <nid004933>
Hello world, I'm rank 35 of 36 total ranks running on <nid004935>
Hello world, I'm rank 5 of 36 total ranks running on <nid004932>
Hello world, I'm rank 6 of 36 total ranks running on <nid004932>
Hello world, I'm rank 3 of 36 total ranks running on <nid004932>
Hello world, I'm rank 4 of 36 total ranks running on <nid004932>
Hello world, I'm rank 7 of 36 total ranks running on <nid004932>
Hello world, I'm rank 2 of 36 total ranks running on <nid004932>
Hello world, I'm rank 17 of 36 total ranks running on <nid004933>
Hello world, I'm rank 32 of 36 total ranks running on <nid004935>
Hello world, I'm rank 28 of 36 total ranks running on <nid004935>
Hello world, I'm rank 18 of 36 total ranks running on <nid004934>
Hello world, I'm rank 1 of 36 total ranks running on <nid004932>
Hello world, I'm rank 21 of 36 total ranks running on <nid004934>
Hello world, I'm rank 0 of 36 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	67.5753 (ms) 
	Sobel time:	5.3431 (ms) 
	Gather time:	57.6349 (ms) 
Hello world, I'm rank 8 of 36 total ranks running on <nid004932>
Hello world, I'm rank 14 of 36 total ranks running on <nid004933>
Hello world, I'm rank 27 of 36 total ranks running on <nid004935>
Hello world, I'm rank 20 of 36 total ranks running on <nid004934>
Hello world, I'm rank 9 of 36 total ranks running on <nid004933>
Hello world, I'm rank 31 of 36 total ranks running on <nid004935>
Hello world, I'm rank 16 of 36 total ranks running on <nid004933>
Hello world, I'm rank 25 of 36 total ranks running on <nid004934>
Hello world, I'm rank 23 of 36 total ranks running on <nid004934>
Hello world, I'm rank 24 of 36 total ranks running on <nid004934>
 srun -n 49 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 8 of 49 total ranks running on <nid004932>
Hello world, I'm rank 31 of 49 total ranks running on <nid004934>
Hello world, I'm rank 22 of 49 total ranks running on <nid004933>
Hello world, I'm rank 21 of 49 total ranks running on <nid004933>
Hello world, I'm rank 7 of 49 total ranks running on <nid004932>
Hello world, I'm rank 41 of 49 total ranks running on <nid004935>
Hello world, I'm rank 43 of 49 total ranks running on <nid004935>
Hello world, I'm rank 45 of 49 total ranks running on <nid004935>
Hello world, I'm rank 32 of 49 total ranks running on <nid004934>
Hello world, I'm rank 29 of 49 total ranks running on <nid004934>
Hello world, I'm rank 26 of 49 total ranks running on <nid004934>
Hello world, I'm rank 35 of 49 total ranks running on <nid004934>
Hello world, I'm rank 34 of 49 total ranks running on <nid004934>
Hello world, I'm rank 30 of 49 total ranks running on <nid004934>
Hello world, I'm rank 16 of 49 total ranks running on <nid004933>
Hello world, I'm rank 23 of 49 total ranks running on <nid004933>
Hello world, I'm rank 13 of 49 total ranks running on <nid004933>
Hello world, I'm rank 12 of 49 total ranks running on <nid004932>
Hello world, I'm rank 17 of 49 total ranks running on <nid004933>
Hello world, I'm rank 28 of 49 total ranks running on <nid004934>
Hello world, I'm rank 36 of 49 total ranks running on <nid004934>
Hello world, I'm rank 20 of 49 total ranks running on <nid004933>
Hello world, I'm rank 3 of 49 total ranks running on <nid004932>
Hello world, I'm rank 9 of 49 total ranks running on <nid004932>
Hello world, I'm rank 11 of 49 total ranks running on <nid004932>
Hello world, I'm rank 25 of 49 total ranks running on <nid004934>
Hello world, I'm rank 27 of 49 total ranks running on <nid004934>
Hello world, I'm rank 6 of 49 total ranks running on <nid004932>
Hello world, I'm rank 47 of 49 total ranks running on <nid004935>
Hello world, I'm rank 37 of 49 total ranks running on <nid004935>
Hello world, I'm rank 38 of 49 total ranks running on <nid004935>
Hello world, I'm rank 10 of 49 total ranks running on <nid004932>
Hello world, I'm rank 2 of 49 total ranks running on <nid004932>
Hello world, I'm rank 4 of 49 total ranks running on <nid004932>
Hello world, I'm rank 33 of 49 total ranks running on <nid004934>
Hello world, I'm rank 1 of 49 total ranks running on <nid004932>
Hello world, I'm rank 18 of 49 total ranks running on <nid004933>
Hello world, I'm rank 14 of 49 total ranks running on <nid004933>
Hello world, I'm rank 48 of 49 total ranks running on <nid004935>
Hello world, I'm rank 39 of 49 total ranks running on <nid004935>
Hello world, I'm rank 24 of 49 total ranks running on <nid004933>
Hello world, I'm rank 19 of 49 total ranks running on <nid004933>
Hello world, I'm rank 40 of 49 total ranks running on <nid004935>
Hello world, I'm rank 5 of 49 total ranks running on <nid004932>
Hello world, I'm rank 44 of 49 total ranks running on <nid004935>
Hello world, I'm rank 42 of 49 total ranks running on <nid004935>
Hello world, I'm rank 46 of 49 total ranks running on <nid004935>
Hello world, I'm rank 15 of 49 total ranks running on <nid004933>
Hello world, I'm rank 0 of 49 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	42.2003 (ms) 
	Sobel time:	3.9749 (ms) 
	Gather time:	42.4503 (ms) 
 srun -n 49 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 40 of 49 total ranks running on <nid004935>
Hello world, I'm rank 38 of 49 total ranks running on <nid004935>
Hello world, I'm rank 29 of 49 total ranks running on <nid004934>
Hello world, I'm rank 17 of 49 total ranks running on <nid004933>
Hello world, I'm rank 19 of 49 total ranks running on <nid004933>
Hello world, I'm rank 30 of 49 total ranks running on <nid004934>
Hello world, I'm rank 47 of 49 total ranks running on <nid004935>
Hello world, I'm rank 45 of 49 total ranks running on <nid004935>
Hello world, I'm rank 27 of 49 total ranks running on <nid004934>
Hello world, I'm rank 12 of 49 total ranks running on <nid004932>
Hello world, I'm rank 28 of 49 total ranks running on <nid004934>
Hello world, I'm rank 37 of 49 total ranks running on <nid004935>
Hello world, I'm rank 39 of 49 total ranks running on <nid004935>
Hello world, I'm rank 43 of 49 total ranks running on <nid004935>
Hello world, I'm rank 21 of 49 total ranks running on <nid004933>
Hello world, I'm rank 23 of 49 total ranks running on <nid004933>
Hello world, I'm rank 48 of 49 total ranks running on <nid004935>
Hello world, I'm rank 13 of 49 total ranks running on <nid004933>
Hello world, I'm rank 32 of 49 total ranks running on <nid004934>
Hello world, I'm rank 1 of 49 total ranks running on <nid004932>
Hello world, I'm rank 14 of 49 total ranks running on <nid004933>
Hello world, I'm rank 33 of 49 total ranks running on <nid004934>
Hello world, I'm rank 42 of 49 total ranks running on <nid004935>
Hello world, I'm rank 26 of 49 total ranks running on <nid004934>
Hello world, I'm rank 36 of 49 total ranks running on <nid004934>
Hello world, I'm rank 16 of 49 total ranks running on <nid004933>
Hello world, I'm rank 8 of 49 total ranks running on <nid004932>
Hello world, I'm rank 18 of 49 total ranks running on <nid004933>
Hello world, I'm rank 22 of 49 total ranks running on <nid004933>
Hello world, I'm rank 24 of 49 total ranks running on <nid004933>
Hello world, I'm rank 2 of 49 total ranks running on <nid004932>
Hello world, I'm rank 20 of 49 total ranks running on <nid004933>
Hello world, I'm rank 5 of 49 total ranks running on <nid004932>
Hello world, I'm rank 7 of 49 total ranks running on <nid004932>
Hello world, I'm rank 31 of 49 total ranks running on <nid004934>
Hello world, I'm rank 9 of 49 total ranks running on <nid004932>
Hello world, I'm rank 15 of 49 total ranks running on <nid004933>
Hello world, I'm rank 41 of 49 total ranks running on <nid004935>
Hello world, I'm rank 35 of 49 total ranks running on <nid004934>
Hello world, I'm rank 46 of 49 total ranks running on <nid004935>
Hello world, I'm rank 25 of 49 total ranks running on <nid004934>
Hello world, I'm rank 44 of 49 total ranks running on <nid004935>
Hello world, I'm rank 4 of 49 total ranks running on <nid004932>
Hello world, I'm rank 34 of 49 total ranks running on <nid004934>
Hello world, I'm rank 0 of 49 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	77.5798 (ms) 
	Sobel time:	4.1305 (ms) 
	Gather time:	79.6723 (ms) 
Hello world, I'm rank 10 of 49 total ranks running on <nid004932>
Hello world, I'm rank 3 of 49 total ranks running on <nid004932>
Hello world, I'm rank 11 of 49 total ranks running on <nid004932>
Hello world, I'm rank 6 of 49 total ranks running on <nid004932>
 srun -n 49 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 27 of 49 total ranks running on <nid004934>
Hello world, I'm rank 32 of 49 total ranks running on <nid004934>
Hello world, I'm rank 11 of 49 total ranks running on <nid004932>
Hello world, I'm rank 44 of 49 total ranks running on <nid004935>
Hello world, I'm rank 4 of 49 total ranks running on <nid004932>
Hello world, I'm rank 41 of 49 total ranks running on <nid004935>
Hello world, I'm rank 48 of 49 total ranks running on <nid004935>
Hello world, I'm rank 38 of 49 total ranks running on <nid004935>
Hello world, I'm rank 12 of 49 total ranks running on <nid004932>
Hello world, I'm rank 42 of 49 total ranks running on <nid004935>
Hello world, I'm rank 3 of 49 total ranks running on <nid004932>
Hello world, I'm rank 36 of 49 total ranks running on <nid004934>
Hello world, I'm rank 30 of 49 total ranks running on <nid004934>
Hello world, I'm rank 9 of 49 total ranks running on <nid004932>
Hello world, I'm rank 33 of 49 total ranks running on <nid004934>
Hello world, I'm rank 18 of 49 total ranks running on <nid004933>
Hello world, I'm rank 34 of 49 total ranks running on <nid004934>
Hello world, I'm rank 15 of 49 total ranks running on <nid004933>
Hello world, I'm rank 19 of 49 total ranks running on <nid004933>
Hello world, I'm rank 2 of 49 total ranks running on <nid004932>
Hello world, I'm rank 8 of 49 total ranks running on <nid004932>
Hello world, I'm rank 13 of 49 total ranks running on <nid004933>
Hello world, I'm rank 47 of 49 total ranks running on <nid004935>
Hello world, I'm rank 26 of 49 total ranks running on <nid004934>
Hello world, I'm rank 43 of 49 total ranks running on <nid004935>
Hello world, I'm rank 31 of 49 total ranks running on <nid004934>
Hello world, I'm rank 1 of 49 total ranks running on <nid004932>
Hello world, I'm rank 37 of 49 total ranks running on <nid004935>
Hello world, I'm rank 7 of 49 total ranks running on <nid004932>
Hello world, I'm rank 28 of 49 total ranks running on <nid004934>
Hello world, I'm rank 29 of 49 total ranks running on <nid004934>
Hello world, I'm rank 45 of 49 total ranks running on <nid004935>
Hello world, I'm rank 39 of 49 total ranks running on <nid004935>
Hello world, I'm rank 23 of 49 total ranks running on <nid004933>
Hello world, I'm rank 16 of 49 total ranks running on <nid004933>
Hello world, I'm rank 46 of 49 total ranks running on <nid004935>
Hello world, I'm rank 20 of 49 total ranks running on <nid004933>
Hello world, I'm rank 14 of 49 total ranks running on <nid004933>
Hello world, I'm rank 40 of 49 total ranks running on <nid004935>
Hello world, I'm rank 24 of 49 total ranks running on <nid004933>
Hello world, I'm rank 5 of 49 total ranks running on <nid004932>
Hello world, I'm rank 21 of 49 total ranks running on <nid004933>
Hello world, I'm rank 10 of 49 total ranks running on <nid004932>
Hello world, I'm rank 25 of 49 total ranks running on <nid004934>
Hello world, I'm rank 17 of 49 total ranks running on <nid004933>
Hello world, I'm rank 6 of 49 total ranks running on <nid004932>
Hello world, I'm rank 0 of 49 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	82.5129 (ms) 
	Sobel time:	3.9884 (ms) 
	Gather time:	56.9453 (ms) 
Hello world, I'm rank 22 of 49 total ranks running on <nid004933>
Hello world, I'm rank 35 of 49 total ranks running on <nid004934>
 srun -n 64 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 34 of 64 total ranks running on <nid004934>
Hello world, I'm rank 40 of 64 total ranks running on <nid004934>
Hello world, I'm rank 47 of 64 total ranks running on <nid004934>
Hello world, I'm rank 28 of 64 total ranks running on <nid004933>
Hello world, I'm rank 18 of 64 total ranks running on <nid004933>
Hello world, I'm rank 20 of 64 total ranks running on <nid004933>
Hello world, I'm rank 9 of 64 total ranks running on <nid004932>
Hello world, I'm rank 15 of 64 total ranks running on <nid004932>
Hello world, I'm rank 42 of 64 total ranks running on <nid004934>
Hello world, I'm rank 41 of 64 total ranks running on <nid004934>
Hello world, I'm rank 23 of 64 total ranks running on <nid004933>
Hello world, I'm rank 30 of 64 total ranks running on <nid004933>
Hello world, I'm rank 3 of 64 total ranks running on <nid004932>
Hello world, I'm rank 45 of 64 total ranks running on <nid004934>
Hello world, I'm rank 8 of 64 total ranks running on <nid004932>
Hello world, I'm rank 52 of 64 total ranks running on <nid004935>
Hello world, I'm rank 35 of 64 total ranks running on <nid004934>
Hello world, I'm rank 51 of 64 total ranks running on <nid004935>
Hello world, I'm rank 53 of 64 total ranks running on <nid004935>
Hello world, I'm rank 61 of 64 total ranks running on <nid004935>
Hello world, I'm rank 44 of 64 total ranks running on <nid004934>
Hello world, I'm rank 32 of 64 total ranks running on <nid004934>
Hello world, I'm rank 25 of 64 total ranks running on <nid004933>
Hello world, I'm rank 49 of 64 total ranks running on <nid004935>
Hello world, I'm rank 19 of 64 total ranks running on <nid004933>
Hello world, I'm rank 56 of 64 total ranks running on <nid004935>
Hello world, I'm rank 38 of 64 total ranks running on <nid004934>
Hello world, I'm rank 21 of 64 total ranks running on <nid004933>
Hello world, I'm rank 50 of 64 total ranks running on <nid004935>
Hello world, I'm rank 36 of 64 total ranks running on <nid004934>
Hello world, I'm rank 31 of 64 total ranks running on <nid004933>
Hello world, I'm rank 46 of 64 total ranks running on <nid004934>
Hello world, I'm rank 11 of 64 total ranks running on <nid004932>
Hello world, I'm rank 16 of 64 total ranks running on <nid004933>
Hello world, I'm rank 48 of 64 total ranks running on <nid004935>
Hello world, I'm rank 37 of 64 total ranks running on <nid004934>
Hello world, I'm rank 39 of 64 total ranks running on <nid004934>
Hello world, I'm rank 26 of 64 total ranks running on <nid004933>
Hello world, I'm rank 1 of 64 total ranks running on <nid004932>
Hello world, I'm rank 4 of 64 total ranks running on <nid004932>
Hello world, I'm rank 17 of 64 total ranks running on <nid004933>
Hello world, I'm rank 59 of 64 total ranks running on <nid004935>
Hello world, I'm rank 2 of 64 total ranks running on <nid004932>
Hello world, I'm rank 58 of 64 total ranks running on <nid004935>
Hello world, I'm rank 10 of 64 total ranks running on <nid004932>
Hello world, I'm rank 13 of 64 total ranks running on <nid004932>
Hello world, I'm rank 7 of 64 total ranks running on <nid004932>
Hello world, I'm rank 6 of 64 total ranks running on <nid004932>
Hello world, I'm rank 29 of 64 total ranks running on <nid004933>
Hello world, I'm rank 14 of 64 total ranks running on <nid004932>
Hello world, I'm rank 60 of 64 total ranks running on <nid004935>
Hello world, I'm rank 63 of 64 total ranks running on <nid004935>
Hello world, I'm rank 33 of 64 total ranks running on <nid004934>
Hello world, I'm rank 57 of 64 total ranks running on <nid004935>
Hello world, I'm rank 27 of 64 total ranks running on <nid004933>
Hello world, I'm rank 62 of 64 total ranks running on <nid004935>
Hello world, I'm rank 43 of 64 total ranks running on <nid004934>
Hello world, I'm rank 22 of 64 total ranks running on <nid004933>
Hello world, I'm rank 12 of 64 total ranks running on <nid004932>
Hello world, I'm rank 54 of 64 total ranks running on <nid004935>
Hello world, I'm rank 24 of 64 total ranks running on <nid004933>
Hello world, I'm rank 5 of 64 total ranks running on <nid004932>
Hello world, I'm rank 55 of 64 total ranks running on <nid004935>
Hello world, I'm rank 0 of 64 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	33.4976 (ms) 
	Sobel time:	3.9703 (ms) 
	Gather time:	50.7663 (ms) 
 srun -n 64 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 23 of 64 total ranks running on <nid004933>
Hello world, I'm rank 30 of 64 total ranks running on <nid004933>
Hello world, I'm rank 19 of 64 total ranks running on <nid004933>
Hello world, I'm rank 9 of 64 total ranks running on <nid004932>
Hello world, I'm rank 21 of 64 total ranks running on <nid004933>
Hello world, I'm rank 31 of 64 total ranks running on <nid004933>
Hello world, I'm rank 17 of 64 total ranks running on <nid004933>
Hello world, I'm rank 1 of 64 total ranks running on <nid004932>
Hello world, I'm rank 14 of 64 total ranks running on <nid004932>
Hello world, I'm rank 49 of 64 total ranks running on <nid004935>
Hello world, I'm rank 20 of 64 total ranks running on <nid004933>
Hello world, I'm rank 28 of 64 total ranks running on <nid004933>
Hello world, I'm rank 44 of 64 total ranks running on <nid004934>
Hello world, I'm rank 33 of 64 total ranks running on <nid004934>
Hello world, I'm rank 45 of 64 total ranks running on <nid004934>
Hello world, I'm rank 55 of 64 total ranks running on <nid004935>
Hello world, I'm rank 56 of 64 total ranks running on <nid004935>
Hello world, I'm rank 27 of 64 total ranks running on <nid004933>
Hello world, I'm rank 12 of 64 total ranks running on <nid004932>
Hello world, I'm rank 16 of 64 total ranks running on <nid004933>
Hello world, I'm rank 50 of 64 total ranks running on <nid004935>
Hello world, I'm rank 25 of 64 total ranks running on <nid004933>
Hello world, I'm rank 26 of 64 total ranks running on <nid004933>
Hello world, I'm rank 18 of 64 total ranks running on <nid004933>
Hello world, I'm rank 22 of 64 total ranks running on <nid004933>
Hello world, I'm rank 60 of 64 total ranks running on <nid004935>
Hello world, I'm rank 62 of 64 total ranks running on <nid004935>
Hello world, I'm rank 46 of 64 total ranks running on <nid004934>
Hello world, I'm rank 4 of 64 total ranks running on <nid004932>
Hello world, I'm rank 24 of 64 total ranks running on <nid004933>
Hello world, I'm rank 58 of 64 total ranks running on <nid004935>
Hello world, I'm rank 59 of 64 total ranks running on <nid004935>
Hello world, I'm rank 3 of 64 total ranks running on <nid004932>
Hello world, I'm rank 7 of 64 total ranks running on <nid004932>
Hello world, I'm rank 13 of 64 total ranks running on <nid004932>
Hello world, I'm rank 5 of 64 total ranks running on <nid004932>
Hello world, I'm rank 36 of 64 total ranks running on <nid004934>
Hello world, I'm rank 15 of 64 total ranks running on <nid004932>
Hello world, I'm rank 8 of 64 total ranks running on <nid004932>
Hello world, I'm rank 37 of 64 total ranks running on <nid004934>
Hello world, I'm rank 48 of 64 total ranks running on <nid004935>
Hello world, I'm rank 38 of 64 total ranks running on <nid004934>
Hello world, I'm rank 35 of 64 total ranks running on <nid004934>
Hello world, I'm rank 63 of 64 total ranks running on <nid004935>
Hello world, I'm rank 6 of 64 total ranks running on <nid004932>
Hello world, I'm rank 51 of 64 total ranks running on <nid004935>
Hello world, I'm rank 41 of 64 total ranks running on <nid004934>
Hello world, I'm rank 47 of 64 total ranks running on <nid004934>
Hello world, I'm rank 42 of 64 total ranks running on <nid004934>
Hello world, I'm rank 54 of 64 total ranks running on <nid004935>
Hello world, I'm rank 11 of 64 total ranks running on <nid004932>
Hello world, I'm rank 32 of 64 total ranks running on <nid004934>
Hello world, I'm rank 39 of 64 total ranks running on <nid004934>
Hello world, I'm rank 34 of 64 total ranks running on <nid004934>
Hello world, I'm rank 52 of 64 total ranks running on <nid004935>
Hello world, I'm rank 53 of 64 total ranks running on <nid004935>
Hello world, I'm rank 61 of 64 total ranks running on <nid004935>
Hello world, I'm rank 2 of 64 total ranks running on <nid004932>
Hello world, I'm rank 43 of 64 total ranks running on <nid004934>
Hello world, I'm rank 0 of 64 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	68.3220 (ms) 
	Sobel time:	3.2518 (ms) 
	Gather time:	56.3833 (ms) 
Hello world, I'm rank 29 of 64 total ranks running on <nid004933>
Hello world, I'm rank 40 of 64 total ranks running on <nid004934>
Hello world, I'm rank 57 of 64 total ranks running on <nid004935>
Hello world, I'm rank 10 of 64 total ranks running on <nid004932>
 srun -n 64 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 6 of 64 total ranks running on <nid004932>
Hello world, I'm rank 9 of 64 total ranks running on <nid004932>
Hello world, I'm rank 14 of 64 total ranks running on <nid004932>
Hello world, I'm rank 12 of 64 total ranks running on <nid004932>
Hello world, I'm rank 18 of 64 total ranks running on <nid004933>
Hello world, I'm rank 15 of 64 total ranks running on <nid004932>
Hello world, I'm rank 1 of 64 total ranks running on <nid004932>
Hello world, I'm rank 5 of 64 total ranks running on <nid004932>
Hello world, I'm rank 30 of 64 total ranks running on <nid004933>
Hello world, I'm rank 44 of 64 total ranks running on <nid004934>
Hello world, I'm rank 40 of 64 total ranks running on <nid004934>
Hello world, I'm rank 38 of 64 total ranks running on <nid004934>
Hello world, I'm rank 4 of 64 total ranks running on <nid004932>
Hello world, I'm rank 20 of 64 total ranks running on <nid004933>
Hello world, I'm rank 8 of 64 total ranks running on <nid004932>
Hello world, I'm rank 3 of 64 total ranks running on <nid004932>
Hello world, I'm rank 31 of 64 total ranks running on <nid004933>
Hello world, I'm rank 2 of 64 total ranks running on <nid004932>
Hello world, I'm rank 59 of 64 total ranks running on <nid004935>
Hello world, I'm rank 45 of 64 total ranks running on <nid004934>
Hello world, I'm rank 13 of 64 total ranks running on <nid004932>
Hello world, I'm rank 58 of 64 total ranks running on <nid004935>
Hello world, I'm rank 25 of 64 total ranks running on <nid004933>
Hello world, I'm rank 50 of 64 total ranks running on <nid004935>
Hello world, I'm rank 11 of 64 total ranks running on <nid004932>
Hello world, I'm rank 22 of 64 total ranks running on <nid004933>
Hello world, I'm rank 28 of 64 total ranks running on <nid004933>
Hello world, I'm rank 21 of 64 total ranks running on <nid004933>
Hello world, I'm rank 63 of 64 total ranks running on <nid004935>
Hello world, I'm rank 24 of 64 total ranks running on <nid004933>
Hello world, I'm rank 54 of 64 total ranks running on <nid004935>
Hello world, I'm rank 10 of 64 total ranks running on <nid004932>
Hello world, I'm rank 27 of 64 total ranks running on <nid004933>
Hello world, I'm rank 26 of 64 total ranks running on <nid004933>
Hello world, I'm rank 33 of 64 total ranks running on <nid004934>
Hello world, I'm rank 34 of 64 total ranks running on <nid004934>
Hello world, I'm rank 42 of 64 total ranks running on <nid004934>
Hello world, I'm rank 52 of 64 total ranks running on <nid004935>
Hello world, I'm rank 49 of 64 total ranks running on <nid004935>
Hello world, I'm rank 39 of 64 total ranks running on <nid004934>
Hello world, I'm rank 36 of 64 total ranks running on <nid004934>
Hello world, I'm rank 41 of 64 total ranks running on <nid004934>
Hello world, I'm rank 7 of 64 total ranks running on <nid004932>
Hello world, I'm rank 32 of 64 total ranks running on <nid004934>
Hello world, I'm rank 53 of 64 total ranks running on <nid004935>
Hello world, I'm rank 35 of 64 total ranks running on <nid004934>
Hello world, I'm rank 43 of 64 total ranks running on <nid004934>
Hello world, I'm rank 47 of 64 total ranks running on <nid004934>
Hello world, I'm rank 46 of 64 total ranks running on <nid004934>
Hello world, I'm rank 56 of 64 total ranks running on <nid004935>
Hello world, I'm rank 29 of 64 total ranks running on <nid004933>
Hello world, I'm rank 23 of 64 total ranks running on <nid004933>
Hello world, I'm rank 0 of 64 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	63.0630 (ms) 
	Sobel time:	3.5081 (ms) 
	Gather time:	76.8712 (ms) 
Hello world, I'm rank 19 of 64 total ranks running on <nid004933>
Hello world, I'm rank 16 of 64 total ranks running on <nid004933>
Hello world, I'm rank 51 of 64 total ranks running on <nid004935>
Hello world, I'm rank 61 of 64 total ranks running on <nid004935>
Hello world, I'm rank 55 of 64 total ranks running on <nid004935>
Hello world, I'm rank 60 of 64 total ranks running on <nid004935>
Hello world, I'm rank 57 of 64 total ranks running on <nid004935>
Hello world, I'm rank 17 of 64 total ranks running on <nid004933>
Hello world, I'm rank 37 of 64 total ranks running on <nid004934>
Hello world, I'm rank 62 of 64 total ranks running on <nid004935>
Hello world, I'm rank 48 of 64 total ranks running on <nid004935>
 srun -n 81 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 1  
Hello world, I'm rank 48 of 81 total ranks running on <nid004934>
Hello world, I'm rank 53 of 81 total ranks running on <nid004934>
Hello world, I'm rank 44 of 81 total ranks running on <nid004934>
Hello world, I'm rank 52 of 81 total ranks running on <nid004934>
Hello world, I'm rank 55 of 81 total ranks running on <nid004934>
Hello world, I'm rank 60 of 81 total ranks running on <nid004934>
Hello world, I'm rank 12 of 81 total ranks running on <nid004932>
Hello world, I'm rank 4 of 81 total ranks running on <nid004932>
Hello world, I'm rank 21 of 81 total ranks running on <nid004933>
Hello world, I'm rank 54 of 81 total ranks running on <nid004934>
Hello world, I'm rank 67 of 81 total ranks running on <nid004935>
Hello world, I'm rank 58 of 81 total ranks running on <nid004934>
Hello world, I'm rank 77 of 81 total ranks running on <nid004935>
Hello world, I'm rank 38 of 81 total ranks running on <nid004933>
Hello world, I'm rank 23 of 81 total ranks running on <nid004933>
Hello world, I'm rank 51 of 81 total ranks running on <nid004934>
Hello world, I'm rank 43 of 81 total ranks running on <nid004934>
Hello world, I'm rank 65 of 81 total ranks running on <nid004935>
Hello world, I'm rank 41 of 81 total ranks running on <nid004934>
Hello world, I'm rank 49 of 81 total ranks running on <nid004934>
Hello world, I'm rank 71 of 81 total ranks running on <nid004935>
Hello world, I'm rank 75 of 81 total ranks running on <nid004935>
Hello world, I'm rank 63 of 81 total ranks running on <nid004935>
Hello world, I'm rank 16 of 81 total ranks running on <nid004932>
Hello world, I'm rank 14 of 81 total ranks running on <nid004932>
Hello world, I'm rank 35 of 81 total ranks running on <nid004933>
Hello world, I'm rank 72 of 81 total ranks running on <nid004935>
Hello world, I'm rank 9 of 81 total ranks running on <nid004932>
Hello world, I'm rank 42 of 81 total ranks running on <nid004934>
Hello world, I'm rank 33 of 81 total ranks running on <nid004933>
Hello world, I'm rank 50 of 81 total ranks running on <nid004934>
Hello world, I'm rank 27 of 81 total ranks running on <nid004933>
Hello world, I'm rank 80 of 81 total ranks running on <nid004935>
Hello world, I'm rank 78 of 81 total ranks running on <nid004935>
Hello world, I'm rank 59 of 81 total ranks running on <nid004934>
Hello world, I'm rank 29 of 81 total ranks running on <nid004933>
Hello world, I'm rank 34 of 81 total ranks running on <nid004933>
Hello world, I'm rank 37 of 81 total ranks running on <nid004933>
Hello world, I'm rank 28 of 81 total ranks running on <nid004933>
Hello world, I'm rank 47 of 81 total ranks running on <nid004934>
Hello world, I'm rank 8 of 81 total ranks running on <nid004932>
Hello world, I'm rank 56 of 81 total ranks running on <nid004934>
Hello world, I'm rank 57 of 81 total ranks running on <nid004934>
Hello world, I'm rank 26 of 81 total ranks running on <nid004933>
Hello world, I'm rank 40 of 81 total ranks running on <nid004933>
Hello world, I'm rank 39 of 81 total ranks running on <nid004933>
Hello world, I'm rank 6 of 81 total ranks running on <nid004932>
Hello world, I'm rank 69 of 81 total ranks running on <nid004935>
Hello world, I'm rank 31 of 81 total ranks running on <nid004933>
Hello world, I'm rank 25 of 81 total ranks running on <nid004933>
Hello world, I'm rank 45 of 81 total ranks running on <nid004934>
Hello world, I'm rank 32 of 81 total ranks running on <nid004933>
Hello world, I'm rank 62 of 81 total ranks running on <nid004935>
Hello world, I'm rank 36 of 81 total ranks running on <nid004933>
Hello world, I'm rank 73 of 81 total ranks running on <nid004935>
Hello world, I'm rank 30 of 81 total ranks running on <nid004933>
Hello world, I'm rank 22 of 81 total ranks running on <nid004933>
Hello world, I'm rank 68 of 81 total ranks running on <nid004935>
Hello world, I'm rank 79 of 81 total ranks running on <nid004935>
Hello world, I'm rank 46 of 81 total ranks running on <nid004934>
Hello world, I'm rank 76 of 81 total ranks running on <nid004935>
Hello world, I'm rank 70 of 81 total ranks running on <nid004935>
Hello world, I'm rank 66 of 81 total ranks running on <nid004935>
Hello world, I'm rank 74 of 81 total ranks running on <nid004935>
Hello world, I'm rank 7 of 81 total ranks running on <nid004932>
Hello world, I'm rank 13 of 81 total ranks running on <nid004932>
Hello world, I'm rank 2 of 81 total ranks running on <nid004932>
Hello world, I'm rank 11 of 81 total ranks running on <nid004932>
Hello world, I'm rank 17 of 81 total ranks running on <nid004932>
Hello world, I'm rank 5 of 81 total ranks running on <nid004932>
Hello world, I'm rank 10 of 81 total ranks running on <nid004932>
Hello world, I'm rank 15 of 81 total ranks running on <nid004932>
Hello world, I'm rank 19 of 81 total ranks running on <nid004932>
Hello world, I'm rank 18 of 81 total ranks running on <nid004932>
Hello world, I'm rank 20 of 81 total ranks running on <nid004932>
Hello world, I'm rank 3 of 81 total ranks running on <nid004932>
Hello world, I'm rank 24 of 81 total ranks running on <nid004933>
Hello world, I'm rank 64 of 81 total ranks running on <nid004935>
Hello world, I'm rank 61 of 81 total ranks running on <nid004935>
Hello world, I'm rank 1 of 81 total ranks running on <nid004932>
Hello world, I'm rank 0 of 81 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	34.8589 (ms) 
	Sobel time:	3.9563 (ms) 
	Gather time:	45.2854 (ms) 
 srun -n 81 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 2  
Hello world, I'm rank 67 of 81 total ranks running on <nid004935>
Hello world, I'm rank 35 of 81 total ranks running on <nid004933>
Hello world, I'm rank 65 of 81 total ranks running on <nid004935>
Hello world, I'm rank 43 of 81 total ranks running on <nid004934>
Hello world, I'm rank 62 of 81 total ranks running on <nid004935>
Hello world, I'm rank 47 of 81 total ranks running on <nid004934>
Hello world, I'm rank 63 of 81 total ranks running on <nid004935>
Hello world, I'm rank 79 of 81 total ranks running on <nid004935>
Hello world, I'm rank 17 of 81 total ranks running on <nid004932>
Hello world, I'm rank 51 of 81 total ranks running on <nid004934>
Hello world, I'm rank 26 of 81 total ranks running on <nid004933>
Hello world, I'm rank 33 of 81 total ranks running on <nid004933>
Hello world, I'm rank 27 of 81 total ranks running on <nid004933>
Hello world, I'm rank 36 of 81 total ranks running on <nid004933>
Hello world, I'm rank 48 of 81 total ranks running on <nid004934>
Hello world, I'm rank 25 of 81 total ranks running on <nid004933>
Hello world, I'm rank 32 of 81 total ranks running on <nid004933>
Hello world, I'm rank 72 of 81 total ranks running on <nid004935>
Hello world, I'm rank 71 of 81 total ranks running on <nid004935>
Hello world, I'm rank 76 of 81 total ranks running on <nid004935>
Hello world, I'm rank 59 of 81 total ranks running on <nid004934>
Hello world, I'm rank 34 of 81 total ranks running on <nid004933>
Hello world, I'm rank 68 of 81 total ranks running on <nid004935>
Hello world, I'm rank 30 of 81 total ranks running on <nid004933>
Hello world, I'm rank 53 of 81 total ranks running on <nid004934>
Hello world, I'm rank 14 of 81 total ranks running on <nid004932>
Hello world, I'm rank 21 of 81 total ranks running on <nid004933>
Hello world, I'm rank 73 of 81 total ranks running on <nid004935>
Hello world, I'm rank 70 of 81 total ranks running on <nid004935>
Hello world, I'm rank 78 of 81 total ranks running on <nid004935>
Hello world, I'm rank 24 of 81 total ranks running on <nid004933>
Hello world, I'm rank 29 of 81 total ranks running on <nid004933>
Hello world, I'm rank 44 of 81 total ranks running on <nid004934>
Hello world, I'm rank 8 of 81 total ranks running on <nid004932>
Hello world, I'm rank 10 of 81 total ranks running on <nid004932>
Hello world, I'm rank 9 of 81 total ranks running on <nid004932>
Hello world, I'm rank 20 of 81 total ranks running on <nid004932>
Hello world, I'm rank 52 of 81 total ranks running on <nid004934>
Hello world, I'm rank 23 of 81 total ranks running on <nid004933>
Hello world, I'm rank 75 of 81 total ranks running on <nid004935>
Hello world, I'm rank 49 of 81 total ranks running on <nid004934>
Hello world, I'm rank 19 of 81 total ranks running on <nid004932>
Hello world, I'm rank 22 of 81 total ranks running on <nid004933>
Hello world, I'm rank 56 of 81 total ranks running on <nid004934>
Hello world, I'm rank 38 of 81 total ranks running on <nid004933>
Hello world, I'm rank 55 of 81 total ranks running on <nid004934>
Hello world, I'm rank 28 of 81 total ranks running on <nid004933>
Hello world, I'm rank 40 of 81 total ranks running on <nid004933>
Hello world, I'm rank 42 of 81 total ranks running on <nid004934>
Hello world, I'm rank 7 of 81 total ranks running on <nid004932>
Hello world, I'm rank 15 of 81 total ranks running on <nid004932>
Hello world, I'm rank 77 of 81 total ranks running on <nid004935>
Hello world, I'm rank 66 of 81 total ranks running on <nid004935>
Hello world, I'm rank 2 of 81 total ranks running on <nid004932>
Hello world, I'm rank 50 of 81 total ranks running on <nid004934>
Hello world, I'm rank 54 of 81 total ranks running on <nid004934>
Hello world, I'm rank 58 of 81 total ranks running on <nid004934>
Hello world, I'm rank 60 of 81 total ranks running on <nid004934>
Hello world, I'm rank 69 of 81 total ranks running on <nid004935>
Hello world, I'm rank 41 of 81 total ranks running on <nid004934>
Hello world, I'm rank 5 of 81 total ranks running on <nid004932>
Hello world, I'm rank 74 of 81 total ranks running on <nid004935>
Hello world, I'm rank 80 of 81 total ranks running on <nid004935>
Hello world, I'm rank 46 of 81 total ranks running on <nid004934>
Hello world, I'm rank 61 of 81 total ranks running on <nid004935>
Hello world, I'm rank 13 of 81 total ranks running on <nid004932>
Hello world, I'm rank 45 of 81 total ranks running on <nid004934>
Hello world, I'm rank 6 of 81 total ranks running on <nid004932>
Hello world, I'm rank 39 of 81 total ranks running on <nid004933>
Hello world, I'm rank 57 of 81 total ranks running on <nid004934>
Hello world, I'm rank 1 of 81 total ranks running on <nid004932>
Hello world, I'm rank 31 of 81 total ranks running on <nid004933>
Hello world, I'm rank 12 of 81 total ranks running on <nid004932>
Hello world, I'm rank 64 of 81 total ranks running on <nid004935>
Hello world, I'm rank 18 of 81 total ranks running on <nid004932>
Hello world, I'm rank 11 of 81 total ranks running on <nid004932>
Hello world, I'm rank 16 of 81 total ranks running on <nid004932>
Hello world, I'm rank 3 of 81 total ranks running on <nid004932>
Hello world, I'm rank 4 of 81 total ranks running on <nid004932>
Hello world, I'm rank 37 of 81 total ranks running on <nid004933>
Hello world, I'm rank 0 of 81 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	57.8497 (ms) 
	Sobel time:	4.1759 (ms) 
	Gather time:	63.7494 (ms) 
 srun -n 81 ./mpi_2dmesh -i ../data/zebra-gray-int8-4x -x 7112 -y 5146 -g 3  
Hello world, I'm rank 24 of 81 total ranks running on <nid004933>
Hello world, I'm rank 1 of 81 total ranks running on <nid004932>
Hello world, I'm rank 53 of 81 total ranks running on <nid004934>
Hello world, I'm rank 33 of 81 total ranks running on <nid004933>
Hello world, I'm rank 16 of 81 total ranks running on <nid004932>
Hello world, I'm rank 28 of 81 total ranks running on <nid004933>
Hello world, I'm rank 45 of 81 total ranks running on <nid004934>
Hello world, I'm rank 25 of 81 total ranks running on <nid004933>
Hello world, I'm rank 46 of 81 total ranks running on <nid004934>
Hello world, I'm rank 77 of 81 total ranks running on <nid004935>
Hello world, I'm rank 6 of 81 total ranks running on <nid004932>
Hello world, I'm rank 8 of 81 total ranks running on <nid004932>
Hello world, I'm rank 10 of 81 total ranks running on <nid004932>
Hello world, I'm rank 36 of 81 total ranks running on <nid004933>
Hello world, I'm rank 63 of 81 total ranks running on <nid004935>
Hello world, I'm rank 43 of 81 total ranks running on <nid004934>
Hello world, I'm rank 13 of 81 total ranks running on <nid004932>
Hello world, I'm rank 30 of 81 total ranks running on <nid004933>
Hello world, I'm rank 73 of 81 total ranks running on <nid004935>
Hello world, I'm rank 11 of 81 total ranks running on <nid004932>
Hello world, I'm rank 60 of 81 total ranks running on <nid004934>
Hello world, I'm rank 56 of 81 total ranks running on <nid004934>
Hello world, I'm rank 34 of 81 total ranks running on <nid004933>
Hello world, I'm rank 72 of 81 total ranks running on <nid004935>
Hello world, I'm rank 40 of 81 total ranks running on <nid004933>
Hello world, I'm rank 17 of 81 total ranks running on <nid004932>
Hello world, I'm rank 80 of 81 total ranks running on <nid004935>
Hello world, I'm rank 19 of 81 total ranks running on <nid004932>
Hello world, I'm rank 15 of 81 total ranks running on <nid004932>
Hello world, I'm rank 76 of 81 total ranks running on <nid004935>
Hello world, I'm rank 51 of 81 total ranks running on <nid004934>
Hello world, I'm rank 54 of 81 total ranks running on <nid004934>
Hello world, I'm rank 47 of 81 total ranks running on <nid004934>
Hello world, I'm rank 44 of 81 total ranks running on <nid004934>
Hello world, I'm rank 65 of 81 total ranks running on <nid004935>
Hello world, I'm rank 70 of 81 total ranks running on <nid004935>
Hello world, I'm rank 75 of 81 total ranks running on <nid004935>
Hello world, I'm rank 23 of 81 total ranks running on <nid004933>
Hello world, I'm rank 5 of 81 total ranks running on <nid004932>
Hello world, I'm rank 66 of 81 total ranks running on <nid004935>
Hello world, I'm rank 12 of 81 total ranks running on <nid004932>
Hello world, I'm rank 26 of 81 total ranks running on <nid004933>
Hello world, I'm rank 4 of 81 total ranks running on <nid004932>
Hello world, I'm rank 9 of 81 total ranks running on <nid004932>
Hello world, I'm rank 22 of 81 total ranks running on <nid004933>
Hello world, I'm rank 57 of 81 total ranks running on <nid004934>
Hello world, I'm rank 64 of 81 total ranks running on <nid004935>
Hello world, I'm rank 55 of 81 total ranks running on <nid004934>
Hello world, I'm rank 78 of 81 total ranks running on <nid004935>
Hello world, I'm rank 29 of 81 total ranks running on <nid004933>
Hello world, I'm rank 35 of 81 total ranks running on <nid004933>
Hello world, I'm rank 59 of 81 total ranks running on <nid004934>
Hello world, I'm rank 39 of 81 total ranks running on <nid004933>
Hello world, I'm rank 37 of 81 total ranks running on <nid004933>
Hello world, I'm rank 50 of 81 total ranks running on <nid004934>
Hello world, I'm rank 58 of 81 total ranks running on <nid004934>
Hello world, I'm rank 48 of 81 total ranks running on <nid004934>
Hello world, I'm rank 2 of 81 total ranks running on <nid004932>
Hello world, I'm rank 79 of 81 total ranks running on <nid004935>
Hello world, I'm rank 14 of 81 total ranks running on <nid004932>
Hello world, I'm rank 18 of 81 total ranks running on <nid004932>
Hello world, I'm rank 71 of 81 total ranks running on <nid004935>
Hello world, I'm rank 74 of 81 total ranks running on <nid004935>
Hello world, I'm rank 31 of 81 total ranks running on <nid004933>
Hello world, I'm rank 0 of 81 total ranks running on <nid004932>


Timing results from rank 0: 
	Scatter time:	55.8545 (ms) 
	Sobel time:	2.9054 (ms) 
	Gather time:	60.5860 (ms) 
Hello world, I'm rank 49 of 81 total ranks running on <nid004934>
Hello world, I'm rank 20 of 81 total ranks running on <nid004932>
Hello world, I'm rank 21 of 81 total ranks running on <nid004933>
Hello world, I'm rank 32 of 81 total ranks running on <nid004933>
Hello world, I'm rank 38 of 81 total ranks running on <nid004933>
Hello world, I'm rank 52 of 81 total ranks running on <nid004934>
Hello world, I'm rank 3 of 81 total ranks running on <nid004932>
Hello world, I'm rank 42 of 81 total ranks running on <nid004934>
Hello world, I'm rank 67 of 81 total ranks running on <nid004935>
Hello world, I'm rank 41 of 81 total ranks running on <nid004934>
Hello world, I'm rank 7 of 81 total ranks running on <nid004932>
Hello world, I'm rank 27 of 81 total ranks running on <nid004933>
Hello world, I'm rank 68 of 81 total ranks running on <nid004935>
Hello world, I'm rank 69 of 81 total ranks running on <nid004935>
Hello world, I'm rank 61 of 81 total ranks running on <nid004935>
Hello world, I'm rank 62 of 81 total ranks running on <nid004935>
```