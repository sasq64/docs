+++
title = "demarc"
template = "demarc.html"
+++



## Main goal

Make it easy to watch demos from C64 and Amiga

* Runs multiple demos in order or shuffled
* Shows demo meta data as overlay
* CRT shader (Lottes) for "authentic" look
* Can run Amiga/Atari/C64 exes & disk images
* Right-Alt hotkey for disk switch etc
* Can run multiple files at once in a grid


## Download (Windows)

Pre-built windows binary [here](/dl/demarc.zip)


## Rust Install

You need [rust](https://rustup.rs).

`cargo install --git https://github.com/sasq64/demarc.git`

## Prepare

Set your monitor to 50Hz if possible.

## Run

`demarc --help`

`demarc --aga --shuffle AmigaAGA/`

*TIP:* Download all intros from [https://intros.c64.org](https://intros.c64.org/]) and run

`demarc --grid=4x3 --shuffle intros_c64_org_12596_full`


## Shortcuts

_Right Alt_ or _Right Ctrl_ +

```
D = Swap disk
N = Next file
S = Change scaling
B = Change border
I = Toggle Info
P = Screenshot
R = Reset
C = Toggle CRT filter
W/SHIFT-W = Warp 10s/30s
J = Toggle Joystick/keyboard

For grid:

TAB = Next emulator
SHIFT+TAB = Previous emulator
ENTER = Maximize/Unmaximize
A = Select all emulators
```
