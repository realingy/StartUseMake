###########################v3
object = main.o test1.o test2.o test3.o

test : $(object)
	g++ -o test $(object)

$(object) : global.h

.PHONY : clean
clean:
	-rm test $(object)

