# ⌚ Relógio T100 Ultra 3

A desktop clock application with a smartwatch-inspired interface, built with Python and PySide6. It combines timekeeping, scheduling, and productivity tools in a single, modern window.

## ✨ Features

- 🕒 **Home dial:** a polished analog watch face with a seconds ring and date window, alongside digital time, a greeting, daily progress, and the next public holiday.
- 🌍 **World clock:** track any IANA time zone, with search and time differences relative to your computer.
- ⏰ **Alarms:** one-time, daily, or weekday schedules, with configurable snooze.
- ⏱️ **Stopwatch:** precise timing with lap and split tracking.
- ⏳ **Timer and Pomodoro:** quick presets, manual entry, and customizable focus and break cycles.
- 📅 **Calendar:** Brazilian national holidays, including movable dates such as Easter, Carnival, and Corpus Christi.
- 🪟 **Compact mode:** a floating, always-on-top mini clock that you can drag anywhere.

Settings are saved automatically, so your time zones, alarms, and Pomodoro preferences persist between sessions.

## 🚀 Getting Started

**Requirements:** Python 3.10 or newer.

```bash
pip install -r requirements.txt
python relogio_t100_gui.py
```

Keep `relogio_t100.py` and `relogio_t100_gui.py` in the same folder. The graphical interface imports the core logic from the first file.

## 🧭 Usage

- Click an app tile to open it, and press `Esc` to return to the home screen.
- Open Compact mode for a floating mini clock. Double-click it to restore the main window.

## ⚙️ Configuration

Settings are stored in `~/.relogio_t100/config.json`. You can edit them through the interface, so manual changes are rarely needed.

## 🛠️ Tech Stack

Python · PySide6 (Qt for Python) · zoneinfo · tzdata
