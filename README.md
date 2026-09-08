# PA2_RAMOS
Problem A: I used np.random.seed(2112) to ensure reproducibility of the integer. and used np.mean() and np.std() to get the overall mean and population standard deviation.  

Problem B:I used np.arange(1, 101) to generate the first 100 positive integers then used (** 3) to cube the integers. I also used (C % 4 == 0) to filter and get all the cubed integers divisible by 4 while preserving the row-major ordering.

Problem C: I used (np.arange(1, 37) ** 2).reshape(6, 6) to generate the 6x6 array with the squares of numbers 1 through 36. I also used np.mean(S) to get the average value of the matrix(S_mean). Then I used S > S_mean to select values greater than the mean.
