AES Encryption using open MPI and openssl
 
On Ubuntu :
Steps to install dependencies:

1. sudo apt-get install -y vim openssl libssl-dev

2. sudo apt-get install libcr-dev mpich mpich-doc


Compile using mpicc:

	mpicc file.c -o file.o -lssl -lcrypto

	./file.o filename