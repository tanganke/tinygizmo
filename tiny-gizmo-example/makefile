executable: example-main.cpp ../tiny-gizmo.cpp
	g++ -g -Wall -Wextra $^ -o $@ -Ithird-party -I. -Ithird-party/glew -Ithird-party/glfw-3.1.2 -lglfw `pkg-config --libs glew` -lGL