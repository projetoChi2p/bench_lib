##################################################################
#
# BENCH library stub function build recipe
#
# This CMake file contains the recipe for building the stub function
# libraries that correlate with the library public API.  This supports
# unit testing of OTHER modules, where the test cases for those modules
# are linked with the stubs supplied here.
#
##################################################################

add_cfe_coverage_stubs(bench_lib bench_lib_stubs.c)

