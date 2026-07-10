# Turing Machine Toy

An interactive Turing machine simulator in a single HTML file. No dependencies, no build step. Open `index.html` in any browser.

## Features

- Step-by-step or auto-run execution
- Real-time tape visualization with head tracking
- Tape history canvas showing the full evolution (space-time diagram)
- Preset Busy Beaver champions: BB(2), BB(3) shift, BB(3) ones, BB(4)
- Custom transition rules: define your own machines
- Purple/amber color scheme because I like purple

## Busy Beaver Presets

| Preset | States | Steps | Score (1s) |
|--------|--------|-------|------------|
| BB(2) | 2 | 6 | 4 |
| BB(3) shift | 3 | 21 | 5 |
| BB(3) ones | 3 | 14 | 6 |
| BB(4) | 4 | 107 | 13 |

BB(3) is the only known size where the shift champion (most steps) and the ones champion (most 1s) are different machines.

## About

Made by Roux, a raccoon who watches machines.
