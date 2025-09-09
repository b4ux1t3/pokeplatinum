# Text Color Palette Indices for TEXT_COLOR Macro

The `TEXT_COLOR(letter, shadow, bg)` macro uses palette indices to select colors for text rendering. Below is a table of common color indices and their typical meanings in Pokémon DS games. Actual colors may vary depending on the font palette loaded in your project.

## Palette Index Table
| Index | Color Name   |
|-------|-------------|
| 0     | Black       |
| 1     | Red         |
| 2     | Green       |
| 3     | Blue        |
| 4     | Light Blue  |
| 5     | Yellow      |
| 6     | Magenta     |
| 7     | Orange      |
| 8     | Brown       |
| 9     | Purple      |
| 10    | Pink        |
| 11    | Gray        |
| 12    | Dark Green  |
| 13    | Navy        |
| 14    | Silver      |
| 15    | White       |

## TEXT_COLOR Macro Arguments

- **letter**: The color index for the main text (foreground/letter color).
- **shadow**: The color index for the drop shadow or outline of the text. Usually set to 0 (black) for best contrast, but can be any palette index.
- **bg**: The color index for the background behind the text. Typically set to 15 (white) or 0 (black), but can be any palette index depending on UI design.

## Example Usages
| Macro Example                | Letter | Shadow | Background | Description                |
|-----------------------------|--------|--------|------------|----------------------------|
| TEXT_COLOR(1, 0, 15)        | Red    | Black  | White      | Red text, black shadow, white bg |
| TEXT_COLOR(2, 0, 15)        | Green  | Black  | White      | Green text, black shadow, white bg |
| TEXT_COLOR(0, 15, 15)       | Black  | White  | White      | Black text, white shadow, white bg |
| TEXT_COLOR(15, 0, 0)        | White  | Black  | Black      | White text, black shadow, black bg |
| TEXT_COLOR(5, 0, 15)        | Yellow | Black  | White      | Yellow text, black shadow, white bg |

**Note:**

- The actual color mapping may depend on the loaded font palette. These are typical assignments for DS Pokémon games.
- You can use any combination for letter, shadow, and background in the macro.
- Refer to your game's font palette resource for exact color values if needed.
