# Rhythm Punch Map Generator

This is the official map generation tool for Rhythm Punch.

It allows you to create custom maps using your own audio files with both:

- Automatic map generation
- Semi-automatic manual mapping editor

---

# Features

## Automatic Generator
Generate complete maps automatically from audio analysis.

Features include:
- Beat and rhythm detection
- Automatic combo generation
- Humanized lane placement
- Multiple difficulty generation
- Obstacle generation
- RPMap export support

---

## Semi-Automatic Mapper (Web Editor)

The semi-automatic editor allows you to manually create the Expert difficulty while the system automatically:

- Generates human-friendly lane placement
- Rebuilds combos
- Creates all lower difficulties
- Reduces notes for each difficulty automatically
- Exports complete RPMap files

Open the editor here:

:contentReference[oaicite:0]{index=0}

---

# Semi-Automatic Mapper Controls

## Basic Controls

| Key | Action |
|---|---|
| Space | Play / Pause |
| Enter | Add obstacle |
| Any letter or number | Add note |
| Delete | Delete selected notes/obstacles |

---

## Navigation

| Key | Action |
|---|---|
| Left Arrow | Backward 1 second |
| Right Arrow | Forward 1 second |
| Up Arrow | Previous block |
| Down Arrow | Next block |

---

## Mouse Controls

| Action | Result |
|---|---|
| Left Click | Select note/obstacle |
| Click + Drag | Multi-selection |
| Ctrl + C | Copy selected notes |
| Ctrl + V | Paste notes |

---

# Semi-Automatic Workflow

1. Load a song
2. Press Play
3. Add notes rhythmically while listening to the song
4. Add obstacles where needed
5. Select a note and apply combos from the combo panel
6. Export the RPMap

The editor automatically:
- Generates Expert flow
- Creates all difficulties
- Reorganizes combos
- Places notes into human-playable lanes
- Generates the final RPMap package

---

# Download

Download the latest automatic generator version from the Releases section.

---

# How to Import Maps Into Rhythm Punch

Copy map files to:

```text
Android\data\com.asderelforge.rythmpunch\files\Maps

Copy audio files to:

```text
Android\data\com.asderelforge.rythmpunch\files\Audio Files
