all:
	f2py -c -m faras faras.f90 --fcompiler=intelem --opt='-fast -axCORE-AVX2 -qopenmp -unroll-aggresive -qopt-prefetch' -liomp5 -lpthread -lm -ldl
