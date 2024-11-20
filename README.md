# Minesweeper in C#

A simple console-based Minesweeper game written in C#. The program generates a board with bombs and allows the user to uncover tiles. The objective is to uncover all tiles without hitting any bombs.

## Features

- Generate a board with a customizable width, height, and number of bombs.
- Reveal tiles and display the number of adjacent bombs.
- Automatically uncover neighboring tiles when a tile with no adjacent bombs is revealed.
- Win or lose the game based on user actions.

## How to Run

1. Copy the provided code into a file named `Program.cs`.
2. Open the file in a C#-compatible IDE such as Visual Studio or Rider, or install the .NET SDK to run the program from the terminal.
3. Compile and run the program using the following command:

   ```bash
   dotnet run .\Program.cs
   ```