# Aura Dental Clinic & Orthodontics

A responsive single-page dental clinic website demo built with React, Tailwind CSS, and Lucide Icons. It provides treatment information and a browser-based appointment request flow for Aura Dental Clinic.

## Features

- Responsive desktop and mobile layout
- Hash-based single-page navigation
- Dental treatment and symptom guides
- Appointment request form with validation
- Appointment request confirmation with reference code
- Locally stored appointment requests using browser `localStorage`
- View and cancel saved appointment requests
- Urgent tooth-pain navigation and contact links
- Educational disclaimer for clinical information

## Treatment Guides

- Braces & Orthodontics
- Retainers & Retention Plans
- Gum Care & Periodontal Therapy
- Tooth Fillings & Cavity Repair
- Scaling & Professional Cleaning
- Professional Teeth Whitening
- Tooth Pain & Urgent Evaluation
- Comprehensive Dental Exam

## Getting Started

No build step or package installation is required.

1. Open `Dental.html` in a modern web browser.
2. Make sure the browser has an internet connection so the CDN dependencies and Google Font can load.
3. Use the navigation buttons to browse treatment guides or submit an appointment request.

For a more reliable local server experience, run any static file server from this folder and open the provided local URL. For example, with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/Dental.html`.

## Available Routes

The site uses URL hash routes, so these pages can be opened directly:

- `#/` - Home page
- `#/book` - Request an appointment
- `#/my-appointments` - View saved appointment requests
- `#/treatments/braces`
- `#/treatments/retainers`
- `#/treatments/scaling`
- `#/treatments/teeth-whitening`
- `#/treatments/general-checkup`
- `#/dental-problems/gum-care`
- `#/dental-problems/cavities`
- `#/dental-problems/tooth-pain`

## Technology

- HTML5
- React 18 via CDN
- Babel Standalone for in-browser JSX compilation
- Tailwind CSS via CDN
- Lucide Icons via CDN
- Browser `localStorage` for demo data persistence

## Important Notes

This is a front-end demonstration only. Appointment requests are not sent to a clinic or backend service; they remain in the current browser's local storage under the key `aura_requests`.

The contact details, address, opening hours, and treatment content are sample data. Replace them with verified clinic information before production use. The information on the website is educational and does not replace an in-person dental consultation or clinical diagnosis.

