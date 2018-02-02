CXX = g++
CXXFLAGS = -Wall -lGLEW -lGL -lGLU -lglut -lglfw

FILE = main

default: 
	$(CXX) ./src/$(FILE).cpp -o ./$(FILE).out $(CXXFLAGS)

and_run: 
	make && ./$(FILE).out