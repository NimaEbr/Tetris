all: compile link

compile:
	g++ -ITetris2/include -c *.cpp

link:
	g++ main.o -o main -LTetris2/lib -lsfml-graphics -lsfml-window -lsfml-system
