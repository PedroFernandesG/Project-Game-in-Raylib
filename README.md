# Bloody War Game - Raylib

## Installing Raylib on Linux

### In the terminal, type the commands:

```
1.sudo apt install build-essential git
2.sudo apt install cmake
3.sudo apt install libasound2-dev mesa-common-dev
libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-
mesa-dev libglu1-mesa-dev
4.git clone https://github.com/raysan5/raylib.git
raylib
5.cd raylib/src/
6.make PLATFORM=PLATFORM_DESKTOP RAYLIB_LIBTYPE=SHARED
7.sudo make install RAYLIB_LIBTYPE=SHARED
```
### 1.Create a folder to open the project

### 2.In the terminal or in VSCode, inside the created folder

### Type the commands:

```
git clone https://github.com/mrcndz/exemplo-raylib.git
cd example-raylib
make all
./nomedojogo
```

## Installing Raylib on Windows

### First we need to download [Git](https://git-scm.com/downloads/win)

### After downloading, configure with the commands:

```
1.git --version (test if downloaded)
2.git config --global user.name (enter your name)
3.git config --global user.email (enter your email address)
```

### Now we download [raylib](https://raysan5.itch.io/raylib/download/eyJpZCI6ODUzMzEsImV4cGlyZXMiOjE3MzQ5MTY3OTl9.CxxBIv0ec4GUpy9RZ8QicgH4R%2bw%3d)

### 1. Create a folder to open the project

### 2. Look for the “raylib” file of type header(raylib\raylib\src\raylib.h) and place it in this folder

### 3. In the terminal or in VSCode, inside the created folder, type the command:

```
git clone https://github.com/mrcndz/exemplo-raylib.git
```

### 4. Open MakeFile and change RAYLIB_PATH(line 30) and COMPILER_PATH(line 33) to the path on your pc

### RAYLIB_PATH = raylib\raylib\src
### COMPILER_PATH = raylib/w64devkit/bin

### 5. In the terminal, compile the program with the command:
```
mingw32-make PLATFORM=PLATFORM_DESKTOP
``` 

### 6. In the terminal, run the program with the command:
```
./GameName
```

## Bloody War Game

### Game developed during the first programming course of the computer engineering course at the computer center(UFPE) of pernambuco, has the idea of being a simple game, made quickly

https://github.com/user-attachments/assets/3b0c4caf-60b8-4e94-bfdd-3532a3022d57







