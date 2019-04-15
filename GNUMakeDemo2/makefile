###########################v2
object = main.o test1.o test2.o test3.o

test : $(object)
	g++ -o test $(object)

main.o : global.h
test1.o : global.h
test2.o : global.h
test3.o : global.h

.PHONY : clean
clean:
	-rm test $(object)

