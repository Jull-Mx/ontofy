# Ontofy

A single-page web app for people accepted in a new city. Search a subject, see
leading universities in 11 countries, tick off the requirements, then search
flights.

No build step and no dependencies: everything is in `index.html`.

## Run it

Open `index.html` in a browser, or serve the folder with any static host
(Netlify, GitHub Pages).

## Settings to change

At the top of the `<script>` in `index.html`:

| Name | What it is |
| --- | --- |
| `MARKER` | Your Travelpayouts partner marker, added to flight searches. Replace `YOUR_MARKER`. |
| `HOUSING_URL` | Link behind the "Find a place to stay" button. |
| `HOUSING_AFFILIATE` | Set to `true` only if `HOUSING_URL` is an affiliate link (shows the notice). |

## Data

- Countries, universities and subject areas are in `COUNTRIES`.
- UK medicine requirements for Estonian applicants are in `MEDUK`.
- How each system reads a qualification is in `HOW`.

## Accuracy

Requirements are a starting checklist built from official pages and guides.
Rules, dates and fees change and differ by programme and nationality, so
confirm every item on the official sites. Details read directly from official
pages were checked on 3 October 2026; the rest, including the university
descriptions and the subject areas each one offers, come from general
knowledge and have not been checked one by one.
