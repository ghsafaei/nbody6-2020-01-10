# nbody6-2020-01-10
https://ftp.ast.cam.ac.uk/pub/sverre/

make clean
make mcluster
./mcluster  -o name-of-file


make clean
make

../Nbody6-last-test2/Ncode/nbody6 <name-of-file.input  > Ttest.log 2>Ttest.err&


https://github.com/smhr/read-nbody


make READ-NBODY-TAIL
make READ-NBODY-RT
make READ-NBODY-2RT


./READ-NBODY-RT OUT3 my_simulation 0 0
 
./READ-NBODY-2RT OUT3 my_simulation 0 0

./READ-NBODY-TAIL OUT3 my_simulation 0 0
