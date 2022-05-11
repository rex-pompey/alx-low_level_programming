# 0x0E-structures_typedef project tasks

dog.h - Define a new type struct dog with the following elements:

  name, type = char *
  age, type = float
  owner, type = char *
  
1-init_dog.c -  function that initialize a variable of type struct dog
  
2-print_dog.c - a function that prints a struct dog

4-new_dog.c - a function that creates a new dog.

  Prototype: dog_t *new_dog(char *name, float age, char *owner);
  You have to store a copy of name and owner
  Return NULL if the function fails
  
 5-free_dog.c - a function that frees dogs
