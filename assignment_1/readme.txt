Assignment done by:	Diogo Almeida
			Rodrigo Ferreira
			
Part 1 of the assignment is solved in part_1.ipynb and requires the decompressed conditions.csv file to work, the paths provided are relative to local spark, changes to paths when it comes to reading
and writing files must be done to accomodate running on aws, along with changing the spark context cell (reversing comments).
The answer for 1.1 is shown in the notebook but is also present in a file, the answer for 1.2 is present in a file in the zipped assignment, but is also printed to a results folder when executed.

Likewise part 2 of the assignment is solved in part_2.ipynb, the running times were long, so for the last exercise, we recommend using the smaller dataset provided, it contains +-1000 movie plots
some of which were manually inserted and altered to better measure the algorithm's performance.
Part 2 takes a long time to run, especially with the band and row values calculated for 2.1, so all tests were done with samples from 0.05 to 0.5.
Similarly to part 1, the paths are also implemented for running with local spark, changes must be done to writing/reading paths to accomodate running on aws, along with changing the spark context cell (reversing comments).  

