.PHONY: all debug release clean

all: debug release

debug: echo-dbg

hello-dbg: echo.cpp
	g++ -g -O0 echo.cpp -o echo-dbg -Wall

release: echo

hello: echo.cpp
	g++ -O2 echo.cpp -o echo -DNDEBUG -Wall

clean:
	rm -f echo