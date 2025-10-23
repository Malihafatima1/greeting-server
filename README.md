# Time-Based Greeting Server

A simple Node.js HTTP server that greets the user based on the current time of day. The server determines the greeting using the hour and responds accordingly.

## Features
- Returns a dynamic greeting depending on the time:
  - Good morning (6 AM – 12 PM)
  - Good afternoon (12 PM – 6 PM)
  - Good evening (6 PM – 9 PM)
  - Good night (9 PM – 12 AM)
  - Default message for other hours
- Handles date and time in **Australia/Brisbane** timezone.
- Built using Node.js HTTP module.

## Files
- `index-with-require.js` – Main server file
- `today.js` – Module to get the current date in Brisbane timezone

## Prerequisites
- [Node.js](https://nodejs.org/en/) installed

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Malihafatima1/greeting-server

    Navigate into the project folder:

    cd <project-folder>

Start the server:

node index-with-require.js

Open your browser and visit:

http://localhost:8080
