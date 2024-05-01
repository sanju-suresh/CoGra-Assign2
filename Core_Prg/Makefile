all: clean gl

gl: tst3d.cpp
	g++ -o gl tst3d.cpp ../include/glad.c -lGL -lglfw -lGLEW -ldl

clean:
	rm -f gl