# 🚕 RideNow – Online Cab Booking System

A full cab-booking web app (Ola/Uber style) with fare engine, live ride simulation and trip history. Built with **HTML, CSS and vanilla JavaScript** (no frameworks, no backend).

## Features
- Pickup / drop selection across 12 real Delhi-NCR landmarks with GPS coordinates
- **Distance calculation** using the Haversine formula (with a road-distance factor)
- **Dynamic fare engine:** base fare + per-km + per-minute + **surge pricing** by time of day + 5% GST
- 5 ride types: Bike, Auto, Mini, Sedan, SUV, each with its own pricing and speed
- **Promo codes** (`FIRST50`, `SAVE20`) and payment options (Cash / UPI / Card / Wallet)
- **Ride now or schedule for later**, with cancellation of scheduled rides
- **Live ride simulation:** driver search → driver assigned (name, car, plate, rating, OTP) → arriving → on trip → arrived, with an animated car on a custom **Canvas map**
- Receipt with full fare breakdown and driver rating
- **Ride history & stats** (rides, total spent, distance, average rating) saved in `localStorage`
- Responsive layout and automatic dark mode

## Tech
HTML5 · CSS3 (Grid, Flexbox, CSS variables, animations) · JavaScript (ES6, Canvas API, Bézier path animation, `requestAnimationFrame`, Web Storage)

## Run locally
Open `index.html` in any browser.

## Future improvements
- Real maps (Leaflet / Google Maps) and live GPS
- Node.js + MongoDB backend with driver & rider accounts
- Payment gateway (Razorpay) and WebSocket-based live tracking
