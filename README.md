# 2_mpi_myCode

compile:

  for random data:
  make rand

  for datasets:
  make datasets
  
run:
  mpirun -np p a.out

(whre p is the num of tasks you want)
for the datasets change the path to the bin file to suit your pc and make sure n < N and d < D
