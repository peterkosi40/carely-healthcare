# Carely — Healthcare Website & Product Experience Demo

Carely is a fictional healthcare digital product concept showcasing the kind of responsive web application a studio could design for a healthcare business.

## Included
- Responsive landing page inspired by the supplied Carely visual reference
- Locally bundled generated hero and diverse clinician portraits
- Clinician directory with specialty filters and live search
- Appointment booking modal with date/time selection and in-browser confirmation
- Patient portal/profile preview
- Mobile navigation and responsive desktop/tablet/mobile layouts
- Accessibility basics: labels, focus styles, dialog semantics, Escape-to-close

## Run locally
Open `index.html` in a modern browser. All photographs are included alongside the HTML, CSS and JavaScript; no separate assets folder is needed. Google Fonts require an internet connection, but system fallbacks are provided.

## Important demo limitations
Carely is not a real healthcare provider. All clinicians, testimonials, statistics and appointment information are fictional examples. Booking and profile actions are front-end demonstrations only: no data is sent to a server, no accounts are created, and no patient records are stored. Do not enter real medical or sensitive personal information.

## Deploy to Cloudflare Pages
Upload all files at the root of a GitHub repository, connect the repository to Cloudflare Pages, select the production branch that exists in GitHub (usually `main`), choose Framework preset `None`, and set the build output directory to `.`. For a static HTML site, leave the build command blank or use `exit 0` if the setup form requires a command.
