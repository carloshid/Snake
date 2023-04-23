# Snake game in MIPS Assembly language

## How to run
1. Install MARS or another MIPS assembler
2. Connect keyboard to MIPS
3. Change Bitmap Display unit height and width to 8, then connect to MIPS
4. Load and run the snake.asm file

## Controls
| Hotkey            | Action               |
| ----------------- | -------------------- |
| w                 | Move up              |
| a                 | Move left            |
| s                 | Move down            |
| d                 | Move right           |
| q                 | Quits                |
| r                 | Restart              |
| p                 | Pause                |

## Map layout
To change the wall layout, change the value of any numbers in the map.txt file to either 0s or 1s. 
The position of each number in the file corresponds to that same position in the display. 
The file should always contain the same number of rows and columns as the display (32 rows, 64 columns).
A 1 corresponds to a wall, and a 0 corresponds to an empty tile.
The file should not contain any characters that are not '0', '1', '\r' or '\n' but if it does, they will be treated as 0s.


