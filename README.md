# Habit Tracker Desktop (Electron)

A desktop version of the Habit Tracker Calendar application built using Electron.

This app wraps the original browser-based habit tracker into a standalone Windows executable.

## Features

- Monthly calendar layout
- Add and delete daily tasks
- Mark tasks as completed
- Completion colour intensity system
- Current streak and longest streak tracking
- Dark mode toggle
- Local data persistence using localStorage
- Standalone Windows installer (.exe)

## Technologies Used

- Electron
- HTML5
- CSS3
- Vanilla JavaScript
- Node.js

## Installation (Windows)

1. Download the latest installer from the **Releases** section.
2. Run `Habit Tracker Setup 1.0.0.exe`.
3. Install and launch.

## Development Setup

Clone the repository:

```bash
git clone https://github.com/dannybirin/habit-tracker-desktop.git
cd habit-tracker-desktop
```
Install dependencies:
```
npm install
```
Run in development mode:
```
npx electron .
```
Build the Windows installer:
```
npm run dist
```
Related Project

Web version: https://github.com/dannybirin/habit_tracker

Then commit + push:

```powershell
git add README.md
git commit -m "Improve README formatting"
git push
```
