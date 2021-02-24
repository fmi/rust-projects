# Rust Projects

**TODO: This is a placeholder for now, until (if) we gather up some actual project demos**

## Games

### Rust-shooter

![demo](./demos/rust-shooter/demo.gif)

Source: https://github.com/andrewradev/rust-shooter

A toy game in Rust. A pretty standard shooter, not a whole lot of extras.

Ideas for features:

- Levels
- Power-ups (text with different colors?)
- Different enemy movements

### Memory game

![demo](./demos/rust-memory-game/demo.gif)

Source: https://github.com/AndrewRadev/rust-memory-game

Another toy game, with animations this time. Demonstrating both how animations could be tackled with GGEZ's built-in loop and how someone might interact with a "tabletop" game rather than a "shooter" game. Though the mouse interaction is, sadly, super hacky.

Ideas for features:

- An actual game. Right now it's just a board with random cards that flip.

## Web

### Spotiferris

<table>
    <tr>
        <td><img src="./demos/rust-spotiferris/image_1.png" /></td>
        <td><img src="./demos/rust-spotiferris/image_2.png" /></td>
    </tr>
</table>

Source: https://github.com/AndrewRadev/rust-spotiferris

The beginnings of a music organization site.

Ideas for features:

- Uploading an actual mp3 file, parsing its metadata using [rust-id3](https://github.com/polyfloyd/rust-id3) and [rust-id3-image](https://github.com/andrewradev/id3-image)
- Playing an mp3 file, why not.
