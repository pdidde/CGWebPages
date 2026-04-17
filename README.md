# CGWebPages

Simple static web pages for CityGateChurch streaming links.

## Project Overview

This repository contains lightweight HTML pages used to publish church streaming pages.

## Pages

- `index.html`: Home page with navigation button(s).
- `watchLive.html`: Embedded live stream page.
- `watchSermon.html`: Sermon page with an embeddable video player and admin source update mode (`?admin=1`).

## Live Site

The site is available at:

- https://youtube.citygatechurch.online

## Get Latest Updates

To update your local copy with the latest changes from `main`:

```bash
git checkout main
git pull origin main
```

## Watch Sermon And Admin Console

- Home page includes a `Watch Sermon` button in `index.html`.
- The Watch Sermon page uses `watchSermon.html` with an iframe source that can be changed in admin mode.
- Admin mode is enabled with `?admin=1` and allows updating/saving the sermon embed URL.

## Repository Structure

```text
CGWebPages/
├── CNAME
├── README.md
├── images/
├── index.html
├── watchLive.html
└── watchSermon.html
```

## Notes

- Keep pages simple and fast-loading.
- Use responsive iframe containers for video embeds.
