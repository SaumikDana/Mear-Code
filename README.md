# Mear-Code
Boundary element method code for fracking for MSc at UT Austin

Modified files ekd_2.f90, ekd_4.f90, ekd_6.f90, ekd_8.f90 and prep.f90 in accordance with the formulation

The difference between WithMKL/src and Without MKL is the presence of Intel MKL routines for operations in WithMKL/src -- I used the gprof tool to recognize computational bottleneck and added MKL routines to ekd_2.f90
