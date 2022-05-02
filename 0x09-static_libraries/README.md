# 0x09. C - Static libraries

Create the static library libmy.a containing all the functions listed

 How to generate a library from C programs in files lib1.c and lib2.c:

 	gcc -c lib1.c lib2.c

 Create a library “libmy.a” using ar:

	ar -cvq libmy.a lib1.o lib2.o

 You can also list the files in a library with ar:

	 ar -t libmy.a

Create a script called create_static_lib.sh that creates a static library called liball.a from all the .c files that are in the current directory
.
