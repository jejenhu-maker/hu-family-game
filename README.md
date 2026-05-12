# Clean Space Master by Kai

A mobile-friendly browser prototype based on Kai's game idea.

## Core Loop

1. Move the vacuum with the joystick.
2. Vacuum trash on the floor.
3. Find treasure chests and collect ruby.
4. When the tank is **FULL**, press **SELL** to turn dust into money.
5. Use money to **UPGRADE** the vacuum.
6. Clear every room and continue to the next one.

## Implemented MVP

- Touch joystick movement
- Auto-suction when the vacuum gets close to trash
- Tank capacity and FULL state
- SELL button that empties the tank and gives money
- Chest rewards that give ruby
- Upgrade panel:
  - Bigger Tank
  - Stronger Suction
  - Faster Wheels
  - Better Sell Price
- Room-complete progression
- Mobile-safe fullscreen canvas

## Tech Stack

- Single-file HTML5 Canvas game
- No build step
- No dependencies

## Run Locally

Serve the folder with any static server, for example:

```bash
npx http-server .
```

Then open the local URL on desktop or mobile.
