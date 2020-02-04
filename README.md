AES Encryption using open MPI and openssl
 
On Ubuntu :
Steps to install dependencies:

1. openssl
	
		sudo apt-get install -y vim openssl libssl-dev

2. mpi

		sudo apt-get install libcr-dev mpich mpich-doc


Compile using mpicc:

		mpicc file.c -o file.o -lssl -lcrypto

		./file.o filename


Encryption key can be configured in the code