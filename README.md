# Event Talks Website

This repository contains a single-page HTML website for a one-day technical talks event. It displays a schedule of talks with speakers, categories, descriptions, and timings, including a lunch break and transitions. Users can search for talks by category.

## Features

*   **Dynamic Schedule:** Displays a full day's schedule of technical talks.
*   **Talk Details:** Each talk includes title, speakers, categories, duration, and a description.
*   **Time Management:** Accurately calculates start and end times, including a 10:00 AM start, 1-hour talks, 10-minute transitions, and a 1-hour lunch break.
*   **Category Search:** Users can filter talks based on keywords in their categories.
*   **Interactive UI:** Subtle "floatable" effect on talk cards and break items on hover.
*   **Visual Enhancements:** Background image and a smooth fade-in animation for schedule items.
*   **Serverless:** The entire application is contained within a single `index.html` file, designed to be served statically.

## Technologies Used

*   **HTML5:** For the page structure.
*   **CSS3:** For styling, including responsive design, animations, and visual effects.
*   **JavaScript (ES6+):** For dynamic content rendering, schedule calculation, and client-side search functionality.

## How to Run Locally

This website is a static HTML file, so it can be easily run using any static file server. A simple way to do this is using Python's built-in HTTP server.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/ajt4717/gcpQwiklabCreated-event-talks-app.git
    cd gcpQwiklabCreated-event-talks-app
    ```

2.  **Start a Local HTTP Server:**
    Open your terminal or command prompt in the cloned repository's directory and run:
    ```bash
    python3 -m http.server 8000
    ```
    (If `python3` is not available, try `python -m http.server 8000`).

3.  **Open in Browser:**
    Open your web browser and navigate to `http://localhost:8000`.

## Usage

*   **View Schedule:** The full day's schedule will be displayed on the page.
*   **Search Talks:** Use the search bar at the top to type in category keywords (e.g., "AI", "Web Dev", "Security") to filter the displayed talks.
*   **Reset Search:** Click the "Reset" button to clear the search filter and view the complete schedule again.

Enjoy exploring the event schedule!
