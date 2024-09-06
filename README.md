# Simple Pomodoro Timer Script

This is a simple shell script that implements the Pomodoro Technique to help manage work sessions and breaks. It runs on macOS and Linux and provides notification alerts.

## How It Works

- The first argument specifies the focus (work) duration in minutes (default: 25 minutes).
- The second argument specifies the break duration in minutes (default: 5 minutes, or 1/5 of the focus time).
- Notifications will alert you when it's time to take a break or resume work.

## Requirements

- macOS: Uses `osascript` for notifications.
- Linux: Uses `notify-send` for notifications.

## Usage

Run the script with optional focus and break durations:

./pomodoro.sh [focus_time] [break_time]

## Example
./pomodoro.sh 30 6
