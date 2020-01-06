# augmentedReality

This does not appear on my github so I cloned it and readded it to mine.

The original link to the project is here https://github.com/FernandoCaudillo10/augmentedReality.

To run:
	
	g++ -std=c++11 src/*.c src/*.cpp test.cpp -I include/ `pkg-config --libs --cflags opencv` -lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl
