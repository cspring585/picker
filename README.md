# Random Name Picker

An interactive, web-based random name selection application designed for classrooms, meetings, workshops, and team events. Built with clean HTML5 Canvas graphics, responsive CSS styling, and vanilla JavaScript.

## Live Demo

* Primary Demo: [picker.allyit.tech](https://picker.allyit.tech/)
* Secondary Demo: [picker.calebspring.com](https://picker.calebspring.com/)

## Features

### Interactive Spinner Wheel
* Built on HTML5 Canvas with smooth 10 second spin animation.
* High resolution graphics with adaptive text scaling for long names.
* Precise angular stopping alignment ensuring fair visual pointer selection.

### Non-Repeating Selection Pool
* Tracks picked names dynamically during a session.
* Removes selected winners from the active pool until all active names have been picked.
* Resets the pool automatically once every active entry has won.

### Winner Celebration
* Visual winner overlay modal appearing immediately when the wheel stops.
* Auto-dismisses after 15 seconds or upon manual overlay click.

### Roster Management Sidebar
* Collapsible sidebar panel accessible via the Toggle List button.
* Automatic sidebar hiding after 30 seconds of user inactivity.
* Add single names or paste comma-separated lists for quick bulk entry.
* Checkbox controls to temporarily enable or disable specific names without deleting them.
* Individual entry removal and single-click Clear All list option.
* Live status counters tracking Unpicked count versus Active Total.

### Data Persistence and File Portability
* Saves entry lists automatically to browser localStorage across sessions.
* Export rosters to plain text (.txt) files.
* Import saved roster text files directly into the application.

### Customization and Responsive UI
* Dark mode and Light mode toggle with automatic preference saving.
* Fluid responsive layout optimized for desktop displays, projectors, and mobile screens.

## Interface Guide

1. Open Roster Sidebar: Click the Toggle List button in the top navigation bar.
2. Add Names: Type a single name or paste a list separated by commas into the input box, then click Add to Wheel.
3. Manage Entries: Uncheck names to temporarily skip them, or click the remove button next to any name to delete it.
4. Spin the Wheel: Click the central SPIN button to launch the selection animation.
5. Save or Load Rosters: Use Export List to download a text file copy, or Import List to reload existing files.
6. Toggle Theme: Click the theme toggle icon in the top header to switch between light and dark visual themes.

## Technical Details

* Frontend: Vanilla HTML5, CSS3, JavaScript (ES6+).
* Graphics: HTML5 Canvas Context 2D.
* Storage: Browser LocalStorage API.
* Dependencies: Zero external runtime libraries or framework dependencies.

## File Structure

* `index.html`: Contains the full application markup, styles, canvas rendering logic, state management, and event handling.
* `README.md`: Project documentation and user instructions.

## Usage

No build step or server setup is required. Open `index.html` directly in any modern web browser or serve the file using any static web server.
