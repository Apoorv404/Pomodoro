# Pomodoro Timer

A productivity timer application based on the Pomodoro Technique, built with Python and tkinter.

## Description

The Pomodoro Timer is a time management tool that helps you break work into focused intervals, traditionally 25 minutes in length, separated by short breaks. This implementation includes:

- 25-minute work sessions
- 5-minute short breaks
- 20-minute long breaks (after 4 work sessions)
- Visual countdown timer
- Progress tracking with checkmarks
- Start and reset functionality

## Features

- Clean and intuitive GUI interface
- Visual tomato timer display
- Color-coded session indicators
  - Green for work sessions
  - Pink for short breaks
  - Red for long breaks
- Session progress tracking with checkmarks
- Ability to start and reset the timer at any time

## Requirements

- Python 3.x
- tkinter (usually comes with Python)

## Usage

1. Run the program:
```
python main.py
```

2. Use the buttons:
   - Click "Start" to begin the Pomodoro timer
   - Click "Reset" to stop and reset the timer

## How It Works

The application follows the Pomodoro Technique pattern:
1. 25 minutes of focused work
2. 5-minute short break
3. Repeat steps 1-2 three times
4. After 4 work sessions, take a 20-minute long break
5. Checkmarks appear to track completed work sessions

## File Structure

- `main.py` - The main application code
- `tomato.png` - Timer background image
- `README.md` - Project documentation
