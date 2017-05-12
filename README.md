# Tic-Tac-Toe
![Animated capture of game window](game_window_capture.gif)

## About
A game of [Tic-Tac-Toe](https://en.wikipedia.org/wiki/Tic-tac-toe) created by [Chris Kempson](http://chriskempson.com/) in C++ with [Simple DirectMedia Layer version 2](https://www.libsdl.org/). This project demonstrates a simple but fully-finished game built as a learning aid. The code is perhaps over-engineered for Tic-tac-toe but will be useful as a base for more advanced games.

## How to Play
This is a two player game. Clicking the mouse on the title screen will advance to the play screen. To place a piece on the grid click the mouse in the desired grid area. Once a win or draw message is display, clicking again will return to the title screen.

## Features
- Game resources (images and sounds) are handled by a resource manager making them easy to use in any class.
- Game states are handled by a state manager for a neater architecture
- Images can easily be scaled by a factor to help create pixelated retro-like graphics
- Fully documented code with documentation generated by [Doxygen](http://doxygen.org)  
- Uses [C++ Core Guidelines](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines) as a style guide
- Cross-platform (or should be, build files and instructions are currently only available for Windows and Visual Studio)

## Compiling

### Windows (Visual Studio)
Download [SDL2-devel-2.0.4-VC.zip](https://www.libsdl.org/release/SDL2-devel-2.0.4-VC.zip) and [SDL2_mixer-devel-2.0.1-VC.zip](https://www.libsdl.org/projects/SDL_mixer/release/SDL2_mixer-devel-2.0.1-VC.zip) and extract both to a location on your computer you'll use for storing libraries.

Setup an environment variable called `CPP_LIBS` and enter the location where you extracted SDL2 and SDL2_mixer.

Finally, copy `SDL.dll` from `SDL2-2.0.4\lib\x86` and from `SDL2_mixer-2.0.1\lib\x86` to the `Debug` and/or `Release` folders (created after you try to compile a debug or release version respectively.

## Assets
All sounds were created with [DefleMask Tracker](http://deflemask.com/) using Nintendo Game boy sound chip emulation. All images were created with the venerable [Microsoft Paint](https://en.wikipedia.org/wiki/Microsoft_Paint).

## Change Log
Please see CHANGELOG.md.

## Licences
Please see LICENCES.md.