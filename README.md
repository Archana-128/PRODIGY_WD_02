# PRODIGY_WD_02
# Stopwatch Application

This project provides a simple stopwatch application built using HTML, CSS, and JavaScript. The stopwatch features start, pause, reset, and lap functionalities, and is styled with a background image and responsive design.

## Features

- **Start**: Begins the stopwatch and updates the display every second.
- **Pause**: Pauses the stopwatch, halting time tracking.
- **Reset**: Stops the stopwatch and resets the elapsed time to zero. Clears the lap records.
- **Lap**: Records the current elapsed time as a lap and displays it in a list.

## Requirements

- A modern web browser with JavaScript support.

## File Structure

- `index.html`: The main HTML file that contains the structure of the stopwatch.
- `styles.css`: (Embedded within the `<style>` tag in HTML) Contains styles for the stopwatch layout.
- `script.js`: (Embedded within the `<script>` tag in HTML) Contains JavaScript code for stopwatch functionality.

## Usage

1. **Open `index.html`** in a web browser.
2. **Interact with the buttons**:
   - **Start**: Click to start the stopwatch.
   - **Pause**: Click to pause the stopwatch.
   - **Reset**: Click to reset the stopwatch to zero and clear lap records.
   - **Lap**: Click to record a lap time, which will be added to the list below the stopwatch display.

## Code Overview

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    ...
</head>
<body>
    <div class="stopwatch">
        <div class="display" id="timeDisplay">00:00:00</div>
        <div class="controls">
            <button id="startButton">Start</button>
            <button id="pauseButton">Pause</button>
            <button id="resetButton">Reset</button>
            <button id="lapButton">Lap</button>
        </div>
        <div class="laps">
            <ul id="lapList"></ul>
        </div>
    </div>
    ...
</body>
</html>
```

### CSS Styling

- **`body`**: Centers the stopwatch on the page and applies background styling.
- **`.stopwatch`**: Styles the stopwatch container.
- **`.display`**: Styles the time display with a large font size.
- **`.controls button`**: Styles the control buttons with padding and background color.
- **`.laps ul`**: Styles the lap list to remove default list styles.

### JavaScript Functionality

- **`formatTime(ms)`**: Converts milliseconds to a formatted time string `HH:MM:SS`.
- **`updateDisplay()`**: Updates the display with the current elapsed time.
- **`startStopwatch()`**: Starts or resumes the stopwatch.
- **`pauseStopwatch()`**: Pauses the stopwatch.
- **`resetStopwatch()`**: Resets the stopwatch and clears lap records.
- **`recordLap()`**: Records and displays the current lap time.

### Event Listeners

- **Start Button**: Calls `startStopwatch()`.
- **Pause Button**: Calls `pauseStopwatch()`.
- **Reset Button**: Calls `resetStopwatch()`.
- **Lap Button**: Calls `recordLap()`.


## Acknowledgements

- Background image sourced from [Future CDN](https://cdn.mos.cms.futurecdn.net/VgGxJABA8DcfAMpPPwdv6a.jpg).

## Deployment
link : 
