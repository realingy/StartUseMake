test : main.o test1.o test2.o test3.o
	g++ -o test main.o test1.o \
	   test2.o test3.o

main.o : main.cpp global.h
	g++ -c main.cpp global.h

test1.o : test1.cpp global.h
	g++ -c test1.cpp global.h

test2.o : test2.cpp global.h
	g++ -c test2.cpp global.h

test3.o : test3.cpp global.h
	g++ -c test3.cpp global.h

.PHONY : clean
clean:
	rm test main.o test1.o test2.o test3.o
