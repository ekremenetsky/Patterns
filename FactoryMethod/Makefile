TARGET=factoryMethod

all: $(TARGET)

$(TARGET): factoryMethod.o
	g++ factoryMethod.o -o $(TARGET)

factoryMethod.o: factoryMethod.cpp
	g++ -c factoryMethod.cpp

clean:
	$(RM) *.o $(TARGET)
