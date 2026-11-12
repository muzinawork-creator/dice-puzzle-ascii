# Dice Puzzle Ascii

A small puzzle game that plays in your terminal.
You are a little blue creature with horns. Push the dice so that dice with the
same number touch each other. When a group is big enough, it disappears and you
get points.

## Download

- [Download the game (zip, 26 KB)](https://github.com/muzinawork-creator/dice-puzzle-ascii/raw/main/dice-puzzle-ascii-v1.0.0.zip)

The zip works on Windows, Mac and Linux. It needs Node.js, and nothing else.

## How to play

1. Install [Node.js](https://nodejs.org) (version 18 or newer)
2. Unzip the file you downloaded
3. Open a terminal in the new folder
4. Run this:

```
node index.js
```

On Linux and Mac you can also run `./index.js`.

## Keys

| Key | What it does |
| --- | --- |
| Arrow keys or `W` `A` `S` `D` | Move |
| `Shift` + arrow | Climb on or off a die |
| `Space` or `Enter` | Back to the title, or start again |
| `Esc` | Back to the title |
| `Q` | Quit |

On the title screen:

| Key | What it does |
| --- | --- |
| `1` | Start an endless game |
| `2` | Start a timed game (3 minutes) |
| Left / Right or `A` / `D` | Change the kind of dice |

## The rules, in short

- You move one cell at a time.
- If you walk into a die, you push it. Stone and iron dice cannot be pushed.
- Dice that touch and show the same number on top make a group.
- A group disappears when it has as many dice as the number on top.
  A group of three threes disappears. A group of two fives disappears.
- If a die with the number 1 is next to a group that disappears, then all the
  1s on the board disappear too. This is called **Nice-One**.
- New dice appear on the board little by little.
- The game ends when the board is full, when you cannot move any more, or when
  the time is up.

## The kinds of dice

| Name | Color | What is special about it |
| --- | --- | --- |
| normal | white | the usual die |
| wood | yellow | it rolls over when you push it |
| ice | blue | it slides a long way when you push it |
| stone | gray | it cannot be pushed |
| iron | red | it cannot be pushed |

You can change the kind of dice on the title screen, so you can play with wood,
ice, stone, iron or a mix of all of them.

## Screenshots

*Add a picture of the game here.*

## License

MIT. See the [LICENSE](LICENSE) file.
