<div align="center">

# 🌉 LLCodeBridge

**Bridge the gap between block coding and real Python.**

Drag blocks, see Python appear live, run your turtle program — no Python installation needed.

[![Latest Release](https://img.shields.io/github/v/release/thechrislewis/LLCodeBridge-releases?label=download&style=for-the-badge&color=6c8ebf)](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Raspberry%20Pi-lightgrey?style=for-the-badge)](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](https://github.com/thechrislewis/LLCodeBridge)

</div>

---

## ⬇️ Download v2.0.0

Pick the right file for your platform:

| Platform | Installer | Portable |
|---|---|---|
| **Windows (x64)** | [LLCodeBridge Setup 2.0.0.exe](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest/download/LLCodeBridge%20Setup%202.0.0.exe) | [LLCodeBridge 2.0.0.exe](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest/download/LLCodeBridge%202.0.0.exe) |
| **Linux (x64)** | [llcodebridge_2.0.0_amd64.deb](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest/download/llcodebridge_2.0.0_amd64.deb) | - |
| **Raspberry Pi** | [llcodebridge_2.0.0_armv7l.deb](https://github.com/thechrislewis/LLCodeBridge-releases/releases/latest/download/llcodebridge_2.0.0_armv7l.deb) | - |

> **Not sure which to pick?**  
> Windows → use the **Installer** `.exe`  
> Linux → use the `.deb` package for your architecture  
> Raspberry Pi → use the `armv7l .deb`

---

## ✨ What Is LLCodeBridge?

LLCodeBridge is a free, offline desktop app for learning Python through Turtle Graphics. It's designed for beginners — especially students aged 8–14 — who are ready to move beyond Scratch but aren't ready for a blank text editor.

**Three panels, side by side:**

```
┌─────────────────────┬────────────────────┐
│                     │  🐢 Canvas         │
│  🧩 Block Workspace │  (turtle output)   │
│  (drag & drop)      ├────────────────────┤
│                     │  🐍 Generated Code │
│                     │  (live Python)     │
└─────────────────────┴────────────────────┘
```

Snap blocks together → Python appears live in the code panel → hit **Run** → your turtle draws on the canvas. No installs, no terminals, no setup.

---

## 🆕 New in v2.0.0

v2.0.0 is a major feature release, expanding LLCodeBridge from a turtle-focused tool into a full beginner Python IDE:

- **New block categories** — Strings, Dictionaries, Convert (type casting), Errors (try/except, raise), Random (randint, uniform, choice, shuffle, seed)
- **World Info** — world map background, lat/lon coordinate conversion, distance and bearing between points
- **AI Chat blocks** — ask an LLM (Ollama/OpenAI/Claude) a question and use the response in your program
- **Four themes** — Dark, Light, High-Contrast Dark, High-Contrast Light
- **Difficulty levels** — control which block categories are visible per session
- **Block search** — Ctrl+F to instantly find any block by name
- **Autosave** — workspace automatically saved and restored between sessions
- **PDF export** — printable worksheet with block canvas screenshot and Python code
- **QR Share** — encode your project as a QR code to load on another device
- **Student Profile** — attach name and class to every saved project and PDF
- **Teacher Mode** — PIN-protected lock with difficulty cap and file restrictions
- **19 bundled examples** — expanded gallery including ISS world map, flood warning map, and all AI behaviours

---

## 🧩 What Can You Build?

### Block Categories

| Category | Blocks |
|---|---|
| 🐢 **Motion** | forward, backward, turn, go to, set heading, home, speed |
| 🖊 **Pen** | pen up/down, colour, width, fill, dot, stamp, clear |
| 🖥 **Screen** | background colour, title, size, hide/show turtle, keyboard events, mainloop |
| 🎨 **Colour** | hex picker, named colour, RGB, random colour |
| 🐢 **Turtle** | create named turtles, all motion/pen blocks per instance |
| 🎵 **Sound** | play notes, melodies, scales, set tempo/instrument/volume |
| 🌍 **Geography** | live earthquake data, UK flood alerts, ISS position |
| 🌐 **World Info** | world map background, lat/lon to turtle coords, distance, bearing |
| 🤖 **AI Chat** | ask LLM prompts, set persona, AI-suggested movement and colours |
| 🤖 **AI Behaviours** | wander, seek, flee, orbit, chase, flee from turtle, zone wandering, collision |
| ⏱ **Timers** | start timer, get elapsed time |
| 🎲 **Random** | randint, uniform, choice, shuffle, seed |
| 🔤 **Strings** | upper, lower, strip, replace, split, join, find, slice, startswith, endswith… |
| 📚 **Dictionaries** | create, get, set, delete, keys, values, contains, length |
| 🔄 **Convert** | int, float, str, bool, list, type |
| ⚠️ **Errors** | try / except, raise |
| ➰ **Core** | loops, lists, maths, logic, variables, functions (from Blockly) |

### Features

- **No Python required** — runs entirely in-app via [Skulpt](https://skulpt.org/)
- **Four themes** — Dark, Light, High-Contrast Dark, High-Contrast Light
- **Difficulty levels** — filter visible blocks from Beginner to Advanced
- **Block search** — Ctrl+F to find any block instantly
- **Autosave** — workspace auto-saved; restore on next launch
- **Example gallery** — 19 bundled starter projects to learn from
- **Block tooltips** — hover any block to see what Python it generates
- **Sound blocks** — compose notes and melodies directly in block programs
- **Geography blocks** — pull live real-world data (earthquakes, UK floods, ISS) into your programs; plot on a world map
- **AI Chat blocks** — ask AI for ideas and use responses in your drawings
- **Turtle collision detection** — Boolean block returns `True` when two named turtles are within a hit distance
- **Save / Load** — `.llcc` project files (Blockly XML in JSON)
- **Export to .py** — share runnable Python scripts
- **Export to PDF** — printable worksheet with code and canvas screenshot
- **QR Share** — scan a QR code to load a project on another device
- **Student Profile** — name and class saved with projects (great for classrooms)
- **Teacher Mode** — PIN-protected session lock with difficulty cap and file restrictions
- **Windows typing** — works reliably on all Windows configurations

---

## 🏫 For Teachers

LLCodeBridge was built with classrooms in mind:

- **Teacher Mode** locks the app with a PIN — set a session label, cap the difficulty level, and optionally restrict file open/save/export
- **Student profiles** attach a name and class to every saved project and PDF export
- **Difficulty levels** let you control exactly which blocks are visible — hide advanced categories until students are ready
- **No accounts, no internet required** — works offline, no data leaves the device

---

## 🔗 Source Code

The full source is on GitHub: **[thechrislewis/LLCodeBridge](https://github.com/thechrislewis/LLCodeBridge)**

Built with [Electron](https://electronjs.org/), [Blockly 10](https://developers.google.com/blockly), [Skulpt](https://skulpt.org/), and [Split.js](https://split.js.org/). No bundler, no framework — vanilla JS ES modules in the renderer.

---

<div align="center">

Made with ☕ by [Chris Lewis](https://github.com/thechrislewis)

</div>
