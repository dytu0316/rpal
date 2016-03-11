Rpal
====

RPAL is a simple functional programming language which is a subset of PAL, a language invented at MIT by Wozencraft and Evans in the early '70s. This is a compiler for RPAL implemented in C++.

How to run the program
======================

1. cd to this directory
2. $ ./run_tests_rpal 		# run rpal to all test cases and output the file into 'rpal_out' directory
3. $ make 					# compile p1
4. $ ./run_tests_p1 		# run p1 to all test cases and output the file into 'out' directory
5. $ ./diff_all 			# diff all p1 output file with rpal output file, 
							# the result will be stored in 'diff_result.out'
6. $ cat diff_result.out 	# show the content of diff_result.out

What's more
===========
$ make cl 					# clean p1 and all .o files in bin as well as output files in 'out' directory
$ ./run_tests_rpal 			# this will clean all the output files in 'rpal_out' directory first

Structrue
=========
. 			makefile, readme, rpal, p1, diff_result.out and all the shell script files to help the test
./bin 		stores all the .o files
./out 		stores all the output files by p1
./rpal_out 	stores all the output files by rpal
./src 		stores all the source code
./tests 	stores all the original test files

BUGS
====
No bugs found, the output files matches exactly with the output files generated by rpal.
