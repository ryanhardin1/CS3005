OBJECTS = hello.o
CXX = g++
FLAGS = -Wall

hello: $(OBJECTS)
	$(CXX) -o hello $(OBJECTS) $(FLAGS)

hello.o: hello.cpp
	$(CXX) -c hello.cpp

.PHONY = clean

clean:
	rm -f hello *.o