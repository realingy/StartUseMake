##########################v1
#test : main.o test1.o \
	test2.o test3.o
#       g++ -o test main.o test1.o \
	   test2.o test3.o

#main.o : main.cpp global.h
#	g++ -o main.o main.cpp global.h

#test1.o : test1.cpp global.h
#	g++ -o test1.o test1.cpp global.h

#test2.o : test2.cpp global.h
#	g++ -o test2.o test2.cpp global.h

#test3.o : test3.cpp global.h
#	g++ -o test3.o test3.cpp global.h

#.PHONY : clean
#clean:
#	-rm test $(object)

###########################v2
#object = main.o test1.o test2.o test3.o

#test : $(object)
#	g++ -o test $(object)

#main.o : global.h
#test1.o : global.h
#test2.o : global.h
#test3.o : global.h

#.PHONY : clean
#clean:
#	-rm test $(object)

###########################vn
object = main.o test1.o test2.o test3.o

test : $(object)
	g++ -o test $(object)

$(object) : global.h

.PHONY : clean
clean:
	-rm test $(object)

