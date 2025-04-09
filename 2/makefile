cc = gcc
object = dog.o blackcow.o turtle.o main.o
animal_exe : $(object)
	$(cc) -o animal.exe $(object)

dog.o : dog.c
	$(cc) -c -o dog.o dog.c

blackcow.o : blackcow.c
	$(cc) -c -o blackcow.o blackcow.c

turtle.o : turtle.c
	$(cc) -c -o turtle.o turtle.c

main.o : main.c
	$(cc) -c -o main.o main.c

.PHONY : clean
clean :
	rm *.o animal.exe