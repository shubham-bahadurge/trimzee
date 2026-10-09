# Trimzee — Your style, on your time

A responsive salon-discovery and booking **front-end demo** for Pune. Built with plain HTML, CSS and JavaScript so it can be hosted as a static site without a build step.

## Features
- Responsive black-and-white design with soft grey backgrounds, inspired by the Trimzee brand reference.
- Search salons by name, area or service; filter service and audience.
- Two clearly labelled sample salons, service menus, stylist selection, date/time selection and payment preference.
- Demo booking history and cancellation, favourites, local profile, and salon listing enquiry.
- Keyboard-friendly dialogs, mobile navigation, and reduced-motion support.

## Run locally
Open `index.html` in a browser. For a local web server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Important demo limitations
This is a front-end prototype, not a production booking service. Salon listings, reviews, times and prices are illustrative. Availability is not live; authentication is not real; online payment is not processed; and bookings/favourites are stored only in the current browser using local storage. The salon enquiry form does not send messages. Production use needs a secure backend/database, verified salon accounts, real-time slot locking, server-side booking/cancellation, authentication and a payment provider.

## Deploy
Connect this GitHub repository to Vercel as a static site. No framework, build command or environment variables are required.
