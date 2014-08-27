run-suite
=========

bash script that runs a test suite on a program, then returns any discrepencies within the tests and the program output.

./runSuite testsuite.txt ./myprogram

testsuite should contain a list of the tests to be run; for each test there should be a corresponding .in and .out file, as well as an optional .args file (takes in any command line arguments)
