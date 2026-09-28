MOVIEBOOK - RENDER READY VERSION

This version intentionally uses ONE FILE: index.html.
CSS and JavaScript are inside index.html, so there is no separate
script.js path problem when deploying to Render.

GitHub:
Upload ONLY index.html to the repository root.

Repository should look like:
moviebook/
  index.html

Render:
1. New -> Static Site
2. Select the GitHub repository
3. Branch: main
4. Build Command: leave empty
5. Publish Directory: .
6. Create Static Site

Features:
- Movie selection
- Show time selection
- Interactive seats
- Booked seats
- Booking summary
- Demo payment
- Booking ID
- Print ticket
- Close-window button

This is a frontend demo. No real payment or database is connected.
