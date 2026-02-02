# Ray Engine

**About the project:**
Ray Engine is a light-weight engine built on raylib for fast and simple 3D game development. 

**How to run the game:**
1. Clone the repository.
2. Use this command on linux: `gcc main.c map.c player.c raycaster.c -o app -lraylib -lm -lpthread -ldl -lrt -lX11`
3. Use this command on windows: `gcc main.c map.c player.c raycaster.c -o app.exe -IC:\raylib\include -LC:\raylib\lib -lraylib -lopengl32 -lgdi32 -lwinmm -lm`
4. Run the game on linux: `./app`
5. Run the game on windows: `./app.exe`
6. For more instructions see https://nothingness-dev.github.io/raycaster-launch/
