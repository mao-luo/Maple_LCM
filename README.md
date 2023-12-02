# Maple_LCM
================================================================================
DIRECTORY OVERVIEW:

mtl/            Mini Template Library
utils/          Generic helper code (I/O, Parsing, CPU-time, etc)
core/           A core version of the solver
simp/           An extended solver with simplification capabilities
README
LICENSE

================================================================================
BUILDING: (release version: without assertions, statically linked, etc)

export MROOT=<minisat-dir>              (or setenv in cshell)
cd { core | simp }
make clean
make

================================================================================
EXAMPLES:

./Maple_LCM ../Nb5T14.cnf

