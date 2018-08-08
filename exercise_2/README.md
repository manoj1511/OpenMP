Time taken to run the c_pi.c

Compile using gcc c_pi.c. 
To Run ./a.out

This is Thread 0
Number of intervals :      1000000, pi = 3.141592650263454800097e+00, delta = -3.32634e-09, time = 0.022131s
Number of intervals :     10000000, pi = 3.141592653484722497126e+00, delta = -1.05071e-10, time = 0.198495s
Number of intervals :    100000000, pi = 3.141592653586568140156e+00, delta = -3.22498e-12, time = 1.958038s
Number of intervals :   1000000000, pi = 3.141592653581098737448e+00, delta = -8.69438e-12, time = 19.932999s

--------------------------------------------------------
Time taken to run the c_pi_solved.c

Compile using gcc -fopenmp c_pi_solved.c. 
To Run ./a.out

Method 1 :: Number of Threads is 4
This is Thread 0
This is Thread 2
This is Thread 1
This is Thread 3
Number of intervals :      1000000, pi = 3.141592650263580033254e+00, delta = -3.32621e-09, time = 0.006005s
Number of intervals :     10000000, pi = 3.141592653484628794303e+00, delta = -1.05164e-10, time = 0.059700s
Number of intervals :    100000000, pi = 3.141592653586362082763e+00, delta = -3.43103e-12, time = 0.518954s
Number of intervals :   1000000000, pi = 3.141592653590463690705e+00, delta = 6.70575e-13, time = 5.132982s

