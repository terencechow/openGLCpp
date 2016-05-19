Installing glfw on mac
1. Download GLFW src
2. cd to directory
3. `cmake .`
4. `make`
5. `sudo make install`

compile with:

g++ main.cpp -lglfw3 -framework Cocoa -framework OpenGL -framework CoreVideo -framework IOKit -o build