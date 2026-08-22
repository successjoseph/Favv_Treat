# Favv_Treat — The Favour Box

![License](https://img.shields.io/badge/license-Apache%202.0-green)
![Language](https://img.shields.io/badge/language-HTML%2FJS-orange)

## Table of Contents
- [About](#about)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Authors and License](#authors-and-license)

## About

Favv_Treat is a single static HTML page ("The Favour Box") advertising a Valentine's Day 2026 gift-box collection for a small gifting business. It presents four curated packages (The Essence, The Charm, The Romance, The Devotion, priced ₦19,000–₦60,000) with contents lists, and lets a visitor pick a package and a recipient ("For Her"/"For Him"), which opens a pre-filled WhatsApp order message (`wa.me`) to the business's number. There is no backend, database, or payment processor — ordering is handled entirely through a WhatsApp handoff. This is a small, real seasonal marketing/sales page rather than a coded application.

## Prerequisites
None — it's a static page that only needs a web browser. It loads Tailwind CSS and Google Fonts from public CDNs.

## Installation
```bash
git clone https://github.com/successjoseph/Favv_Treat.git
cd Favv_Treat
```
Open `Index.html` directly in a browser, or serve the folder with any static file server.

## Configuration
There is no external configuration file. The WhatsApp contact number (`2347064568787`) and the four package names/prices are hardcoded inline in the page's `<script>` block.

## Usage
Open `Index.html`. Click "Select Package" on any of the four packages, choose "For Her" or "For Him" in the modal, and you are redirected to WhatsApp with a pre-filled order message including the package name and price.

## Testing
No automated tests are currently included (there is no application logic beyond the static page and one small script).

## Contributing
This is a personal/small-business project and isn't set up for outside contributions, though it is licensed permissively (see below).

## Authors and License
**Author:** [successjoseph](https://github.com/successjoseph)
Licensed under the **Apache License, Version 2.0** — see the `LICENSE` file in the repository.
