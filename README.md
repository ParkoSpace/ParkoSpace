# ParkoSpace India 

A peer-to-peer parking marketplace for India. Space owners list their driveways and private parking areas. People looking for parking find and contact them directly through a live map. No middlemen, no booking fees.

Built with Flask, Google Maps, and a dark-themed frontend. Designed and developed in Andhra Pradesh.

---

## What It Does

**For people looking for parking**

- Open the map and allow location access, or search for any area in India
- Browse nearby parking spots shown as price pins on a live Google Map
- Call the owner directly from the listing card
- Navigate to the spot using the built-in Google Maps link

**For space owners**

- Register with a phone number and email OTP verification
- List a parking space with title, location, dimensions, and pricing
- Edit or remove listings at any time from the owner dashboard
- Listings stay active until you mark them as booked or delete them

---

## Tech Stack

| Layer       | Technology                                      |
|-------------|-------------------------------------------------|
| Backend     | Python, Flask                                   |
| Database    | SQLite (local) or PostgreSQL via Supabase        |
| Maps        | Google Maps JavaScript API, Places API          |
| Auth        | Email OTP via external OTP service, Flask sessions with 30-day cookies |
| Frontend    | Vanilla JS, Tailwind CSS (CDN), Lucide Icons    |
| Fonts       | Bebas Neue, Space Grotesk, JetBrains Mono       |
| Hosting     | Gunicorn-compatible, deployable on Render, Railway, or any VPS |

---


