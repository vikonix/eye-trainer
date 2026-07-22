# Eye Trainer

A single-file browser app for eye-movement exercises. A glowing dot moves across the screen along different paths; you follow it with your eyes to train tracking, saccades, and focus.

## Usage

Open `eye-trainer.html` in any modern browser. No build step, no dependencies, no server required.

## Modes

- **Horizontal** / **Vertical** - straight left-right and up-down sweeps.
- **Diagonals** - two diagonals between the top-center and the bottom corners (a V shape).
- **Circle CW** / **Circle CCW** - clockwise and counter-clockwise loops.
- **Figure-8 H** / **Figure-8 V** - horizontal and vertical figure-eight paths.
- **Saccades** - jumps between random points to train quick eye movements.
- **Zoom** - the dot grows and shrinks in place to train accommodation.

## Controls

Keyboard:

- `Space` - pause / play
- `<-` / `->` - previous / next mode
- `up` / `down` - speed
- `T` - toggle light / dark theme
- `A` - cycle auto mode-switch (off / 15s / 30s)
- `H` - hide the panel
- `F` - toggle fullscreen

Mouse:

- Single click on the background - show / hide the panel
- Double click on the background - toggle fullscreen
- Drag the panel's title bar - move the panel around
- `Hide panel` button - hide the panel

## Settings

Speed, dot size, auto-switch, blink reminder, theme, selected mode, and panel position are saved to the browser's `localStorage` and restored automatically on the next visit.

## Blink reminder

When enabled, a gentle on-screen reminder appears every ~20 seconds to prompt you to blink, which helps reduce eye strain during longer sessions.

## License

See `LICENSE`.
