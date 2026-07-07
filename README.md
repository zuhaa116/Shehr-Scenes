# Shehr Scenes

Shehr Scenes is a web platform connecting people across Pakistan to cultural, social, and educational events. It focuses on improving accessibility for students and underinformed communities, while giving entrepreneurs and organizers a platform to showcase their events to a wider audience.

## Live Demo

 https://zuhaa116.github.io/Shehr-Scenes/

## Key Features

- City-based browsing for discovering events in different regions
- Event categories and filters for easier navigation
- Community pages highlighting local engagement and groups
- Signup and login flow for user access
- Contact form for inquiries and support

## Tech Stack

- HTML
- CSS

## Project Structure

```
shehr-scenes/
├── intro.html          Landing page with welcome screen, entry point to the site
├── explore.html         Hub page combining cities, events preview, and login
├── home.html            Main home page with hero section and highlights
├── cities.html          City selection page
├── lahore.html          City-specific events (Lahore)
├── karachi.html         City-specific events (Karachi)
├── islamabad.html       City-specific events (Islamabad)
├── peshawar.html        City-specific events (Peshawar)
├── sialkot.html         City-specific events (Sialkot)
├── multan.html          City-specific events (Multan)
├── events.html          Full event listing with category filters
├── communities.html     Community groups and pages
├── profile.html         User profile and contact page
├── signup.html          User registration page
├── style.css            Shared stylesheet for all pages
├── images/               Project images and assets
├── .gitignore           Git ignore configuration
└── README.md            This file
```

## How to Run Locally

1. Clone or download this repository to your computer.
2. Make sure the `images` folder is present alongside the HTML files.
3. Open `intro.html` in a web browser to start from the welcome page.
4. Navigate through the site using the navigation menu.

## Navigation Overview

- **Home**: Main landing experience with featured events and calls to action
- **Cities**: Browse events by major Pakistani city (Lahore, Karachi, Islamabad, Peshawar, Sialkot, Multan)
- **Events**: Full event listing with category filters (music, education, fashion, sports)
- **Communities**: Community groups (women entrepreneurs, startups, cultural organizations)
- **Profile**: User profile and contact information

Every page shares the same navbar and footer, so all sections are reachable from anywhere on the site.

## Status

This is a front-end prototype. Login and signup forms accept any input and do not connect to a backend or database. Event data is currently hardcoded per page rather than pulled from a shared data source.

## Browser Compatibility

Works on modern browsers including Chrome, Firefox, Safari, and Edge.

## Copyright

© 2026 ZuhaaNadeem, Eman Fatima, Emaan Abrar. All rights reserved. This project and its content, including code, design, and assets, may not be copied, reproduced, or reused without permission.
