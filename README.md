# Atlas

Hello, and welcome to Atlas on Github.
This is where all of our code lives!

# Getting Started

If you aren't familiar with git or github, you may want to read about them here:

[Git](https://git-scm.com/book/en/v1/Getting-Started)

[Github](https://github.com/getting-started)


Github also allows the downloading of zip files for projects, which skips most of those steps.
Though, we recommend that you learn git anyway.

# Setup Guide for Projects

We use Cmake for our C++ projects, this allows users to build projects without distributing massive project files.

You will need to download and install [CMake](https://cmake.org/download/). 3.5 or above!
Make sure you add CMake to your path. The installer will offer to add CMake to your path, but this may not always work.
It can be added manually, but the steps for doing it depend on your operating system.
A quick internet search should return plenty of examples on how to do this.

## Windows:

Windows setup has been configured for use with [Visual Studio](https://www.visualstudio.com/vs/community/).

If Cmake and Visual Studio are properly installed on your computer, you should be able to run our setup.cmd from the file explorer.
When the script has completed execution, you can close the console window.
The script should create a build directory, and fill it with a bunch of Visual Studio specific files, including the .sln file that you can open the project with.

## Linux:

```
cd path/to/folder
./setup
```
