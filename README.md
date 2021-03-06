# Avalonia-Minesweeper-Demo
A demonstration cross platform NET Core Minesweeper clone using the Avalonia UI. 

This is really just something I quickly put together to get a feel of how Avalonia works.

https://github.com/AvaloniaUI/Avalonia

This is not the best platform for writing any game. If writing a game is your aim there are much better cross platform choices.

## Installation

This game requires you to install the .NET Core Runtime for your chosen OS.

https://www.microsoft.com/net/download/

To run the included binary, download Minesweeper-Binary.zip > Unzip > open the containing directory and at a console window type: 

```
dotnet Minesweeper.dll
```

Avalonia is still in Beta currently but this should run on Windows, macOS and Linux (with a GUI).


## Minesweeper Play Instructions

The object of the game is to locate all the mines as quickly as possible. 

The 16 by 16 grid has 40 hidden mines in total.

The game is lost when a tile that the player clicks open contains a mine.

The game begins upon opening the first tile, which also starts the timer (displayed above the top left of the grid).

The first tile clicked never contains a mine.

To open a tile click the left mouse button over the tile.

When a tile is successfully opened without containing a mine, it shows a number. The number indicates the number of mines that exist in the eight tiles touching the tile the number was in.

If the number would have been a 0, the number 0 is not shown, and all tiles touching that square are opened as well.

A flag may be placed on a tile by clicking the right mouse button over a tile. This is to mark a tile as a mine. The flag may also be removed by clicking the right mouse button over the tile again.

Each time a tile is flagged, the number of mines left (displayed above the top right of the grid) is decremented.

The game can be restarted at any time be left clicking on the smiley face (displayed over top center of the grid).

