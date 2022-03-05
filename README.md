# Rust Projects

These are links to projects from the ["Programming with Rust"](https://fmi.rust-lang.bg/) course of the Sofia University in Bulgaria.

The elective course includes 23(ish) lectures spread out over 4 months or so. The students have homework assignments to practice Rust, and, at the end, present a project of their own choosing using the language. Here are some of them:

- [Console](#console)
- [Desktop](#desktop)
- [Distributed](#distributed)
- [Games](#games)

## Console

### Rgit (2021)

Source: <https://github.com/Stuksi/rgit>

![demo](./demos/rgit/demo.gif)

A git-like version control system.

### Coolio (2021)

Source: <https://github.com/pepilipep/coolio>

![demo](./demos/coolio/demo.gif)

coolio is a CLI tool which enables some extra features for your Spotify. Features:

- Automated playlists for artists
- Listen history tracking

### Rust Shell (2020)

Source: <https://github.com/luchev/rush>

![demo](./demos/rush/demo.gif)

A working shell that passes all the compatibility tests from the [build-your-own-shell](https://github.com/tokenrove/build-your-own-shell) project.

### Yit (2020)

Source: <https://github.com/yzelova/Yit>

![demo](./demos/yit/demo.gif)

A git clone with support for branching, diffs and merges.

### Rufile (2020)

Source: <https://github.com/lachaka/rufile>

![demo](./demos/rufile/demo.png)

A console file manager with content previews and a Vim-like command-line.

## Desktop

### RustyEngine (2021)

Source: <https://github.com/NikiNatov/RustyEngine>

https://user-images.githubusercontent.com/124255/155875776-584054bc-ddd7-4365-a98a-c9d568bac555.mp4

A game engine that uses DirectX 11 for rendering as well as Win32 API for its other systems, making it support Windows OS only. Currently implemented features:

- Input and event systems
- Window system
- Model loading (currently FBX format only)
- PBR materials
- Image based lighting and HDR environment maps
- Scene system
- Level editor

### Brainfuck visualizer (2020)

Source: <https://github.com/vtklisurov/RustProject>

![demo](./demos/brainfuck-visualizer/demo.gif)

> This is a Brainfuck interpreter and visualizer, created for my Rust course in uni as a final project. Needs gtk-rs to work.

### Seam carving implementation (2020)

Source: <https://github.com/DannyStoyanov/seam-carving>

| Before                                  | After                                   |
| ---                                     | ---                                     |
| ![demo](./demos/seam-carving/demo1.png) | ![demo](./demos/seam-carving/demo2.png) |

> Seam-carving is an algorithm for content-aware image resizing. It allows image to be resized without losing important content from scaling or cropping.

## Distributed

### Copper (2020)

Source: <https://github.com/TsvetelinKostadinv/Copper>

> The aim is to develop the infrastructure for distributed computing with Rust so a heavy task can be split between multiple computers.
>
> The application has 2 main components
>
> - Server, which accepts connections and sends out tasks
> - Client which receives the task, performs it and returns a result

## Games

### Puker (2021)

Source: <https://github.com/PavelSarlov/puker>

https://user-images.githubusercontent.com/124255/155875841-ef592cc6-eb51-4451-968f-b19b04e4be48.mp4

A simple 2D game made with ggez, inspired by The Binding of Isaac.

### Blackjack (2021)

Source: <https://github.com/KristiyanCvetanov/Blackjack>

![demo](./demos/blackjack/demo.gif)

A simple Blackjack game on Rust using the ggez framework. You play 1vs1 against the dealer with standard blackjack rules, but there are added "power-ups" to help you win.

### Flappy Ferris (2021)

Source: <https://github.com/geosabev/FMI-Rust-2021-2022/tree/main/flappy-ferris>

![demo](./demos/flappy-ferris/demo.gif)

This game is made with ggez and is based on the famous Flappy Bird that was a total hit a couple of years ago.

### Jet Fighter (2021)

Source: <https://github.com/AngelMarinski/FMI-Rust/tree/main/Jet-Fighter>

https://user-images.githubusercontent.com/77447043/155611425-24e76ffa-a258-45a3-bef0-1f5628e571d7.mp4

Jet Fighter is an old arcade game played by two. The winner is whoever shoots their opponent 5 times first.

### Rust-snek (2021)

Source: <https://github.com/teodorask/rust-snek>

https://user-images.githubusercontent.com/124255/156885872-b1158347-518e-4954-9b09-e6e8f877ce02.mp4

> You're playing as a snake livng on a small hexagonal island in the The Big Void. You're lonely and hungry. There's no one else there with you, but there's always exactly one apple. You're goal is to roam the land and eat as many as you can. But beware of the island edges - once you fall you're journey's over! You hope that once you become bigger and stronger you could finally leave. But you'll soon find out that that has its consequences too...

### 5x5 Tic-tac-toe (2020)

Source: <https://github.com/bhristova/rust/tree/master/project/tic_tac_toe>

![demo](./demos/5x5-tic-tac-toe/demo.gif)

> This is an alternative version of the game Tic Tac Toe, where the board consists of 25 cells (5x5) and in order to win, you need to have four consecutive cells with your mark.

### Tetris with ggez (2020)

Source: <https://github.com/vasilp98/Tetris>

<img src="./demos/tetris/demo.gif" width="60%" />

### Tetris with termion (2020)

Source: <https://github.com/nnyx7/tetris-cl>

![demo](./demos/tetris-cl/demo.gif)

### Boids (2020)

Source: <https://github.com/Ivaylogi98/boids_rust_project>

![demo](./demos/boids/demo.gif)

### Digger (2020)

Source: <https://github.com/Zarazen/digger>

![demo](./demos/digger/demo.gif)

### Become_Me (2020)

Source: <https://github.com/IvayloKiryazov/Become_Me>

![demo](./demos/become_me/demo.png)

> Become me is a turn-based strategy game with the goal of taking over the map through adapting, picking the right moment, and plotting with and against your fellow players.

### Tower defense (2020)

Source: <https://github.com/genchev99/rust-game>

![demo](./demos/tower_defense/demo.gif)

### 2-Modded Chess (2020)

Source: <https://github.com/rejnhed/2-modded-chess>

![demo](./demos/2-modded-chess/demo.png)

> Chess with King of the hill & 3-Check written in Rust with ggez
