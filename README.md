
# 🚑 Ambulance Finder Bangladesh

A fast, mobile-friendly web app to find an ambulance in Bangladesh. Search by district, area or name, then call the service directly or send your request on WhatsApp.

**[Live demo](https://YOUR-USERNAME.github.io/ambulance-finder-bd/)** · Single HTML file · No build step · No dependencies

![Intro screen of Ambulance Finder Bangladesh](docs/screenshots/01-intro.png)

## Why

In an emergency, people lose time searching Facebook groups and scattered directories for a working ambulance number. This project puts numbers from many public sources in one searchable, phone-friendly page.

## Screenshots

### Home

![Home screen with search filters and action buttons](docs/screenshots/02-home.png)

### Search results

![List of ambulance services with Call and WhatsApp buttons](docs/screenshots/03-listings.png)

### Pop-up forms

| Send an urgent request | List your ambulance |
|:---:|:---:|
| ![Urgent request form](docs/screenshots/05-send-urgent-request.png) | ![Form to list an ambulance](docs/screenshots/04-list-your-ambulance.png) |

## Features

- Animated intro: an ambulance drives across the screen, then the search opens
- Search by district, area or name, or by phone number
- One-tap **Call** button and **WhatsApp** button (shown only for mobile numbers)
- Other numbers for the same service shown under each card
- **Send urgent request** pop-up: fills a ready message (patient, pickup, hospital, contact) that is attached to the WhatsApp link
- **List your ambulance** pop-up for adding a new service
- Always-visible **Call 999** bar
- White and red theme, keyboard accessible, respects reduced-motion settings


## Data and disclaimer

- Numbers were collected from public directories and lists. They may be outdated or wrong.
- Availability and fares are **not** listed. Always confirm by phone.
- Listings added through the form are stored only in the visitor's own browser. There is no shared database yet.
- This is not an official emergency service. In a life-threatening emergency call **999**.
- If you run a listed service and want your entry changed or removed, please open an issue.


## Contributing

Corrections are the most useful contribution. If a number is wrong, bounces, or has changed, open an issue or a pull request that edits the `data` array. Please include how you checked the number.

## License

MIT. See [LICENSE](LICENSE).

