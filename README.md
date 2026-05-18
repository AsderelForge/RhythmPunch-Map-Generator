# Rhythm Punch Map Generator

This is the official map creation toolkit for Rhythm Punch.

It allows you to create custom maps using your own audio files with both:

* Automatic map generation
* Semi-automatic web-based mapping editor

---

# Features

## Automatic Generator

Generate complete playable maps automatically from audio analysis.

Features include:

* Beat and rhythm detection
* Automatic combo generation
* Humanized lane placement
* Multi-difficulty generation
* Obstacle generation
* RPMap export support
* Automatic flow reconstruction
* Combo rebuilding system

---

# Semi-Automatic Mapper (Web Editor)

The semi-automatic mapper is a browser-based editor focused on fast and efficient rhythm map creation.

The editor allows you to manually create maps while the system automatically handles:

* Humanized lane generation
* Combo reconstruction
* Difficulty generation
* Combo rebuilding after note reduction
* Playable flow generation
* RPMap packaging/export

Open the editor here:

https://asderelforge.github.io/RhythmPunch-Map-Generator/

---

# Current Editor Features

## Audio Features

* Load songs directly in the browser
* Drag & drop audio support
* Song metadata reading
* Real-time playback synchronization
* Timeline playback cursor

---

## Mapping Features

* Add notes in real time while listening
* Add obstacles during playback
* Multi-selection support
* Individual note selection
* Copy / paste note groups
* Delete selected notes or obstacles
* Multiple editable difficulties
* Automatic difficulty generation
* Automatic combo generation
* Combo clearing tool
* RPMap import support
* RPMap export support

---

# Difficulty System

The editor supports:

* Expert
* Hard
* Normal
* Easy

Each difficulty can be edited independently.

When exporting:

* Missing difficulties are generated automatically
* Existing difficulties are preserved
* The highest available difficulty becomes the generation base

Examples:

* If only Expert exists → Hard/Normal/Easy are generated
* If only Normal exists → Normal becomes the base difficulty
* If Hard and Easy exist → Hard becomes the generation base while Easy is preserved

---

# Combo System

The editor supports manual and automatic combo workflows.

Available combo types include:

* Jab Cross
* Hook Combo
* Flow Left
* Flow Right
* Boxing Flow
* Uppercuts
* Uppercut Flow

Additional tools:

* Auto Combo generation
* Combo rebuilding
* Clear Combo tool

Directional attacks are displayed visually using arrow symbols.

---

# Controls

## Basic Controls

| Key                  | Action                          |
| -------------------- | ------------------------------- |
| Space                | Play / Pause                    |
| Enter                | Add obstacle                    |
| Any letter or number | Add note                        |
| Delete               | Delete selected notes/obstacles |

---

## Navigation

| Key         | Action            |
| ----------- | ----------------- |
| Left Arrow  | Backward 1 second |
| Right Arrow | Forward 1 second  |
| Up Arrow    | Previous block    |
| Down Arrow  | Next block        |

---

## Mouse Controls

| Action       | Result               |
| ------------ | -------------------- |
| Left Click   | Select note/obstacle |
| Click + Drag | Multi-selection      |
| Ctrl + C     | Copy selected items  |
| Ctrl + V     | Paste selected items |

---

# Semi-Automatic Workflow

1. Load a song
2. Press Play
3. Add notes rhythmically while listening
4. Add obstacles where needed
5. Apply combos manually or use Auto Combo
6. Edit multiple difficulties if desired
7. Export the RPMap

The editor automatically:

* Generates playable lane flow
* Rebuilds combo structures
* Generates missing difficulties
* Reduces note density for lower difficulties
* Preserves existing manual difficulties
* Creates the final RPMap package

---

# RPMap Support

The editor supports:

* RPMap export
* RPMap loading/importing
* Editing existing maps
* Re-exporting modified maps

---

# Download

Download the latest automatic generator version from the Releases section.

---

# How to Import Maps Into Rhythm Punch

Copy RPMap files to:

Android\data\com.asderelforge.rythmpunch\files\Maps


Copy audio files to:

Android\data\com.asderelforge.rythmpunch\files\Audio Files


---

# Important Notice

This tool does NOT include, distribute, or provide any music or copyrighted content.

Users are solely responsible for ensuring they have the legal rights to use any audio files.

This tool is not affiliated with, endorsed by, or associated with any music labels, artists, or rights holders.

This tool is not intended to be used for copyright infringement or unauthorized use of protected content.

---

# Disclaimer

This tool is provided "as is" without warranties of any kind.

The developer is not responsible for how this tool is used or for any content processed by the user.

---

# Source Code

The source code is not publicly available.
