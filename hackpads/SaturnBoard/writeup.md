# Writeup | SaturnBoard
Orginal repo: https://github.com/regular030/SaturnBoard

## Overview
- This device functions as both a calculator and a macro pad.
- Key gestures include:
  - 7 + 8 + 9: Switches between calculator and macro modes.
  - + and - in calculator mode: Opens the Windows calculator.

## PCB
- All footprints and libraries are sourced from Joe Scotto.
- Wiring conventions:
  - Vertical diodes: Red wire
  - Horizontal diodes: Blue wire

## CAD
- For 3D printing, use **hackpadCase_WithoutPCB.step**
- To visualize the assembled unit, use **hackpadCase_WithPCB.step**
- Corner holes have a diameter of **2.9mm**

## Firmware
- More macros coming soon
- ex: 
  - Open Spotify
  - Open Discord
  - Open YT
  - Copy
  - Paste as plain text (idk how I could do this)
- .uf2 file is in hackpads/SaturnBoard/firmware/hackpad_fireware/build/rp2040.rp2040.seeed_xiao_rp2040/hackpad_fireware.ino.uf2
