# Keyboard Key Capture Tool

(c) J~Net 2026 jnetai.com

---

## Overview

This is a simple HTML page to **capture keyboard keys and their codes** directly on screen.  
It is especially useful for identifying **media keys** (Play/Pause, Next Track, Previous Track) or other custom keys for use in web apps or music players.

Unlike console-based solutions, this tool shows **everything on the page in a status box** with a live press counter.

---

## Features

- Detects any key press
- Shows:
  - `keyCode` (numeric value)
  - `key` (human-readable key name)
  - `code` (physical key code)
  - `location` (standard, left, right, numpad)
  - `count` (number of times the key was pressed)
- Dark theme for easy visibility
- Press the same key multiple times to confirm the correct key code

---

## Usage

1. Open `keys.html` in a modern web browser.
2. Press any key you want to test.
3. Observe the **key information and counter** in the central status box.
4. Use the captured `keyCode` or `code` values to map keys in your JavaScript projects.

---

## Example

Pressing the **Play/Pause media key** may show:
