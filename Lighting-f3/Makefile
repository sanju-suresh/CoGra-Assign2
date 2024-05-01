all: clean gl

gl: light.cpp
	g++ -o gl light.cpp ../include/glad.c -lGL -lglfw -lGLEW -ldl

clean:
	rm -f gl