# latex2image-web

> LaTeX to image converter with web UI using Node.js / Docker

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**latex2image-web** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

LaTeX to image converter with web UI using Node.js / Docker

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | Express.js |
| **Package Manager** | — |

### Dependencies

**Runtime Dependencies:**
- `bluebird`
- `body-parser`
- `express`
- `express-promise-router`
- `express-queue`
- `sharp`
- `shelljs`


---

## Repository Structure

```
latex2image-web/
├── .gitignore
├── LICENSE
├── README.md
├── app.js
├── package-lock.json
├── package.json
├── screenshots
├── static/
│   ├── custom.css
│   ├── index.html
│   ├── latex2image-client.js
│   ├── logo.svg
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `LICENSE` | Source file |
| `README.md` | Source file |
| `app.js` | Source file |
| `package.json` | Source file |
| `screenshots/main.png` | Source file |
| `static/custom.css` | Source file |
| `static/index.html` | Source file |
| `static/latex2image-client.js` | Source file |
| `static/logo.svg` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
# 1. Clone the repository
git clone git@github.com:unacademy/latex2image-web.git
cd latex2image-web

# 2. Install dependencies
npm install      # or yarn install
```

### Available Scripts

```bash
# test
npm run test   # echo "Error: no test specified" && exit 1

```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

_No infra configuration detected._

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> # LaTeX2Image

![Image](screenshots/main.png)

A Node.js web application that allows LaTeX math equations to be entered and converted to PNG/JPG/SVG images.

For each conversion, an isolated Docker container with a LaTeX installation is started; it compiles the generated `.tex` file and converts it to an SVG vector image. If required, the SVG file is then converted to a raster image format for PNG/JPG using [sharp](https://sharp.pixelplumbing.com/).

Bootstrap and jQuery are used in the web interface, with AJAX calls made to the conversion API endpoint.

## Live Demo

The application is access

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
