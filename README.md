# 5-Minute Relaxation App

## Overview

The 5-Minute Relaxation App is a simple, browser-based application designed to guide users through a short relaxation session. It's perfect for quick breaks during work or study sessions to help reduce stress and improve focus.

## Features

- 5-minute guided relaxation session
- Visual timer display
- Voice guidance for each relaxation step
- Start and stop functionality
- Responsive design for various screen sizes
- Wake lock to prevent screen from turning off during the session

## How It Works

The app guides users through the following steps:

1. 30 seconds of free thinking
2. 2 minutes of no thoughts, focusing on a distant object
3. 40 seconds of deep breathing
4. 40 seconds of a chosen relaxation technique
5. 40 seconds of acknowledging thoughts from the previous work session
6. 50 seconds of planning the next task

## Usage

1. Open the HTML file in a web browser.
2. Click the "Start Relaxation" button to begin the session.
3. Follow the voice guidance and on-screen instructions for each step.
4. The timer will count down from 5:00 minutes.
5. You can stop the session at any time by clicking the "Stop" button.
6. Once the session is complete, you'll hear a completion message.

## Technical Details

- Built using HTML, CSS, and JavaScript
- Uses the Web Speech API for voice guidance
- Implements the Wake Lock API to keep the screen active during the session

## Browser Compatibility

This app works best on modern browsers that support the Web Speech API and Wake Lock API. For the best experience, use the latest versions of Chrome, Edge, or Firefox.

## Customization

You can easily customize the relaxation steps by modifying the `relaxationSteps` array in the JavaScript code. Each step object contains a `duration` (in seconds) and a `message` to be spoken and displayed.

## Installation

No installation is required. Simply download the HTML file and open it in a web browser.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features.

## License

This project is open source and available under the MIT License.
