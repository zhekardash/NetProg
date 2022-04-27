.PHONY: all debug release clean

all: debug release

debug: daytime-dbg

hello-dbg: daytime.cpp
	g++ -g -O0 daytime.cpp -o daytime-dbg -Wall

release: daytime

hello: daytime.cpp
	g++ -O2 daytime.cpp -o daytime -DNDEBUG -Wall

clean:
	rm -f daytime