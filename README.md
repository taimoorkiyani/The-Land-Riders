# The-Land-Riders

🚴‍♂️ The Land Riders – Muzaffarabad Ride Service 🌄 is a local ride-hailing web app with separate dashboards for customers, riders, and admins. It offers easy booking, ride management, and secure system control for smooth and reliable city travel.

This repository currently contains a single-page frontend (HTML/CSS/JS) demo.

## What I fixed and completed
- Cleaned and consolidated the large HTML file (removed duplicated blocks and syntax issues).
- Implemented JavaScript for login tab switching, basic validation, loading screen behavior, and simple dashboard switching logic.
- Added Leaflet map initialization centered at Muzaffarabad (approx. lat 34.37, lon 73.47).
- Added a working WhatsApp contact link.
- Tidied markup for better accessibility and responsive behavior.

## How to test locally
1. Clone the repository:
   - git clone https://github.com/taimoorkiyani/The-Land-Riders.git
2. Open the corrected HTML in a browser:
   - Navigate to the repository folder and open `deepseek_html_20260114_a367db.html` in your browser.
   - Or serve it via a simple HTTP server (recommended to avoid mixed content issues with some browsers):
     - Python 3: `python -m http.server 8000` then open `http://localhost:8000/deepseek_html_20260114_a367db.html`
3. Use the login tabs:
   - Try "Customer" login: any non-empty phone & password will show the customer dashboard and map (demo).
   - Try "Rider" login: provide a numeric rider ID (3-6 digits) to view rider dashboard stub.
   - Admin login: any non-empty admin name & password shows admin stub.

Notes:
- This is a static demo and contains client-side stubs only (no real authentication, no backend).
- To make it a full app, integrate with your chosen backend (APIs for auth, booking, rider locations, etc.).

## Next recommended steps
- Add server-side APIs for authentication and bookings (Node/Express, Django, etc.).
- Replace demo login/register flows with secure endpoints (HTTPS, hashed passwords, tokens).
- Add real rider live-tracking (WebSocket or polling) and booking persistence (database).
- Improve map UX: autocomplete, routing, distance/fare estimate.

If you'd like, I can:
- Prepare a PR with these corrected files,
- Or create a branch and push these changes if you give me the repo write instruction/permission.
