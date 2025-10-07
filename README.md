🧭 Holland Compass
A personal, editable travel guide to the Netherlands, designed for friends and visitors starting their journey from Utrecht.

This web application serves as a dynamic, multilingual guide featuring city information, one-day trip planning, practical tips, and cultural insights about the Netherlands. The content is fully editable by the owner through a secure login, using Firebase as a real-time database.

✨ Key Features
Utrecht-Centric Guides: Detailed information on cities to visit, with travel times and distances calculated from Utrecht.

Editable Content: The site owner can log in to add, edit, or delete places (museums, restaurants, monuments), curiosities, and practical information in real-time.

One-Day Itinerary Planner: A tool to generate sightseeing routes for a specific city, including points of interest and restaurants.

Google Maps Integration: Every location has a direct link to open in Google Maps, and itineraries can generate a followable route.

Multilingual Support: The entire site can be switched between English, Spanish, Catalan, and Galician.

Cultural & Practical Info: Dedicated sections for:

"Know Utrecht": A deep dive into the home city.

Useful Dutch phrases.

Cultural curiosities.

Information on transport (NS trains) and supermarkets.

Secure Contact Form: A backend-powered contact form that sends emails without exposing the owner's email address.

🛠️ Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ESM)

Backend: Vercel Serverless Functions (Node.js)

Database: Google Firebase (Firestore) for real-time data storage.

Email: Nodemailer for handling contact form submissions.

Deployment: Vercel

⚙️ Setup and Configuration
To run this project, you need to set up the following environment variables in your Vercel project settings:

Name

Value

VITE_FIREBASE_CONFIG

The Firebase config object for your web app (as a single line of text).

GMAIL_USER

Your full Gmail address for the contact form.

GMAIL_APP_PASSWORD

A 16-character Google App Password for Nodemailer.

