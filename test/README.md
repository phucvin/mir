cd ..

make

./c2m sieve.c -S

time ./c2m sieve.c -ei

time ./c2m sieve.c -eg

time ./c2m sieve.c -el

./c2m c2mir/c2mir.c c2mir/c2mir-driver.c mir.c mir-gen.c -eg sieve.c -S