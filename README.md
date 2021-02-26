# Rust Projects

**TODO: Some of these are placeholders for now, until we gather up enough actual project demos**

- [Desktop](#desktop)
- [Distributed](#distributed)
- [Games](#games)
- [Web](#web)

## Desktop

### Brainfuck visualizer

Source: https://github.com/vtklisurov/RustProject

![demo](./demos/brainfuck-visualizer/demo.gif)

> This is a Brainfuck interpreter and visualizer, created for my Rust course in uni as a final project. Needs gtk-rs to work.

## Distributed

### Copper

Source: https://github.com/TsvetelinKostadinv/Copper

> The aim is to develop the infrastructure for distributed computing with Rust so a heavy task can be split between multiple computers.
>
> The application has 2 main components
>
> - Server, which accepts connections and sends out tasks
> - Client which receives the task, performs it and returns a result

## Games

### Rust-shooter (placeholder)

![demo](./demos/rust-shooter/demo.gif)

Source: https://github.com/andrewradev/rust-shooter

A toy game in Rust. A pretty standard shooter, not a whole lot of extras.

Ideas for features:

- Levels
- Power-ups (text with different colors?)
- Different enemy movements

### Memory game (placeholder)

Source: https://github.com/AndrewRadev/rust-memory-game

![demo](./demos/rust-memory-game/demo.gif)

Another toy game, with animations this time. Demonstrating both how animations could be tackled with GGEZ's built-in loop and how someone might interact with a "tabletop" game rather than a "shooter" game. Though the mouse interaction is, sadly, super hacky.

Ideas for features:

- An actual game. Right now it's just a board with random cards that flip.

## Web

### Spotiferris (placeholder)

Source: https://github.com/AndrewRadev/rust-spotiferris

| The song listing                                      | Editing a song                                        |
| --                                                    | --                                                    |
| ![demo image 1](./demos/rust-spotiferris/image_1.png) | ![demo image 2](./demos/rust-spotiferris/image_2.png) |

The beginnings of a music organization site.

Ideas for features:

- Uploading an actual mp3 file, parsing its metadata using [rust-id3](https://github.com/polyfloyd/rust-id3) and [rust-id3-image](https://github.com/andrewradev/id3-image)
- Playing an mp3 file, why not.
