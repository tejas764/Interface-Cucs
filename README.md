# Interface — Festival Landing Page

A static event website for INTERFACE 2025–2026, with a neon visual theme, event sections, and team profiles.

**Stack:** HTML · CSS · Bootstrap · AOS · Font Awesome

## Features

- Festival hero and section navigation
- Technical and non-technical event cards
- University information, team profiles, and contact section
- Scroll animations and responsive Bootstrap layout

## Run locally

```bash
git clone https://github.com/tejas764/Interface-Cucs.git
cd Interface-Cucs
```

Open `index.html` directly, or run `python -m http.server 8000` and visit http://localhost:8000. Python is only required for this optional local server. Internet access is needed for the CDN styles, scripts, and fonts.

## Project structure

| Path | Purpose |
| --- | --- |
| [index.html](index.html) | Page content and markup |
| [styles.css](styles.css) | Main visual theme |
| [event.css](event.css) | Event-card styles |
| [team.css](team.css) | Team section styles |
| [hover.css](hover.css) | Hover effects |
| [mk.jpg](mk.jpg) | Included profile image |

## Current scope

This repository is the static presentation layer. Registration, brochure downloads, and several event links currently use `#` placeholders. It does not contain a registration backend. Replace placeholder links, profile imagery, and contact details before publishing for a new event.

## Related repositories

- [Interface-2026](https://github.com/tejas764/Interface-2026): backend snapshot with missing application components.
- [interface-3](https://github.com/tejas764/interface-3): registration server with frontend and model directories.

## Contributing

Keep changes focused, describe how to reproduce or verify them, and preserve existing attribution. Never include credentials or personal datasets in a contribution.
