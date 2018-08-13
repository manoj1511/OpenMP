Time taken to run c_daxpy.c 

compile using g++ c_daxpy.c
run using ./a.out

Length of vectors :      1000000, Total amount of memory : 0.02 GB, time = 1.209e-02s   
Length of vectors :     10000000, Total amount of memory : 0.22 GB, time = 1.198e-01s   
Length of vectors :    100000000, Total amount of memory : 2.24 GB, time = 5.990e+00s  

-------------------------------------------------------------------------------------
Time taken to run c_daxpy_solved.c

compile using gcc -fopenmp c_daxpy_solved.c 
run using ./a.out

Method 1 :: Number of Threads is 4
Length of vectors :      1000000, Total amount of memory : 0.02 GB, time = 7.758e-03s  
Length of vectors :     10000000, Total amount of memory : 0.22 GB, time = 7.991e-02s  
Length of vectors :    100000000, Total amount of memory : 2.24 GB, time = 1.280e+00s  

