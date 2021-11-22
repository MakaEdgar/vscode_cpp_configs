# VsCode C++ configs for Linux

VsCode configs for building and debugging c++ code under linux + corresponding `.gitignore` that filters garbage.
The build keys are the same as in the homework tests on github.

The run/build tasks will compile all `*.cpp` files in `.` directory into `./out` binary.
Therefore you must have only one `main` function in these files.
My approach is to comment all lines in all test files except the one I want to build.

Note: under Windows all commands must be executed in WSL. 
To start WSL press `Win+R`, type `bash` and press `Enter`.
More convenient option is to type `bash` in [Address Bar of Windows Explorer](https://uis.georgetown.edu/file-explorer/#parts) and press `Enter`. 
<br/><br/>

## Prerequisites
1. For Windows: install WSL and Lunix distribution (e.g. Ubuntu)
2. [Install](https://stackoverflow.com/questions/66223241/how-to-install-clang-11-on-debian) clang++-11
3. Install gdb
4. Install VsCode
<br/><br/>

## Usage under Windows via WSL
Copy the `.vscode` folder to the code folder and run ` code .`
Win GUI starts, and you can run normal debugging with `F5`, build project with ` Ctrl + Shift + B`, and the compiler messages match those of github tests.
Despite the Windows interface, the commands are executed in WSL ubuntu.
<br/><br/>

## Usage under Linux
Just copy the `.vscode` folder to the code folder and run ` code .` or open application.

<br/><br/>
---
In case of any questions write me directly in slack/TG.

(c) Makarov Edgar 2021 <makaed@yandex.ru>
