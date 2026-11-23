# AREEV 2025 Conference Website

This repository contains the website for **AREEV 2025 - International Conference on Advances in Renewable Energy & Electric Vehicles**. The conference was organized by the Department of Electrical and Electronics Engineering at NMAM Institute of Technology, Nitte.

AREEV 2025 ran as part of the International Conference on Emerging Trends in Engineering (ICETE 2025) on **6-7 February 2025** in an offline format.

## Website sections

The homepage presents the following conference information:

- Conference welcome and event summary
- About Nitte (Deemed to be University)
- About NMAM Institute of Technology
- About the Organizing Department
- Conference theme and objectives
- Thrust areas:
  - Advances in Renewable Energy Systems
  - Electric Vehicles
  - Control Systems
  - Power Converters and Drives for EV
- Invited speakers
- Eligible participants
- Publications and conference proceedings
- Journals accepted for extended versions
- Important dates
- Paper submission guidance
- Registration fees
- Mode of payment
- Conference location
- Contact details
- Committee information, including patrons, chairs, conveners, organizing committee, and technical advisory committee

## Technology

This is a static conference website built with:

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap
- Bootstrap Icons
- Font Awesome
- AOS (Animate On Scroll)
- GLightbox
- Swiper
- Isotope
- PureCounter

The PHP files in `forms/` contain template contact form handlers, but this repository's homepage is static and does not require PHP to run.

## Run locally

From the repository root, start a local HTTP server:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/` in a browser.

You can also open `index.html` directly, or use a static-site/live-server extension in an editor. An HTTP server is recommended for consistent asset loading.

## Project structure

```text
.
├── index.html
├── assets/
│   ├── css/
│   ├── img/
│   ├── js/
│   ├── scss/
│   └── vendor/
├── forms/
└── README.md
```

## Template attribution

The site is based on the BootstrapMade **UpConstruction** template.

- Template: https://bootstrapmade.com/upconstruction-bootstrap-construction-website-template/
- BootstrapMade: https://bootstrapmade.com/

### Vendor documentation notes

The small `Readme.txt` files under `forms/` and `assets/scss/` are template attribution notes supplied with the UpConstruction theme. They describe optional pro-template features and should not be treated as separate project READMEs.

Existing BootstrapMade and template license notices in the repository are retained. This README does not replace or add a blanket project license.
