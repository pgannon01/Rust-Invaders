# Rust Invaders

A simple game based around the old Space Invaders game, but built completely in Rust!

Built for a class, a nice little way to practice and learn new skills in Rust.

# Controls

Arrow keys to move left and right

Spacebar to shoot

Q or Esc to quit the game

## Quick Side Note

Has sounds included into the game, so be wary if you're not expecting them!

## How to Start

To start the game, first download the files and install Rust onto your computer.

Then, if you're on a Windows, in your console, cd into the download folder, where the Cargo.toml file is located and type: cargo run

This should start the game in your console. On Linux, and possibly Mac, you will need to install some dependencies.

Firstly you'll need CentOS, then Debian/Ubuntu. Simply do the following commands in your console:

``` bash
sudo yum install -y alsa-lib-devel 
```

and:

```bash
sudo apt install libasound2-dev pkg-config
```