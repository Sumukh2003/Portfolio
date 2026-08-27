# Portfolio Website

## Overview

Single-file portfolio for Sumukh P Marathe, Full Stack Developer. Everything (HTML, CSS, JS)
lives in `index.html` — open it in a browser or drop it on any static host.

## Design

"Signal" — a Swiss-poster direction: strict grid, one loud accent (`#FF4A17`), outline display
type, tabular data. Light and dark palettes are both defined and follow the visitor's system
setting.

## Structure

Sticky left rail (brand, numbered nav with scrollspy, contact links) beside a scrolling content
column:

| Section    | Contents                                                       |
| ---------- | -------------------------------------------------------------- |
| Intro      | Wordmark, status, lead, stack ticker, facts band, metrics band |
| Profile    | Summary                                                         |
| Work       | Experience entries with bullets and stack chips                 |
| Projects   | Five project rows that invert to accent on hover (top two link live) |
| Skills     | Label/value matrix: languages, backend, frontend, data, real-time, cloud, tooling |
| Background | Education and certifications                                    |
| Contact    | Full-bleed accent block with email, phone and profiles          |

## Details

- Responsive from 320px up; the rail collapses to a horizontal nav below 1040px
- Scroll reveals, ticker and pulse all switch off under `prefers-reduced-motion`
- Type: Archivo (variable width axis), Public Sans, Roboto Mono — via Google Fonts
- The hero wordmark is measured and fitted to its column on load and on resize, so it never overflows
- Content tracks the resume in `Sumukh_Marathe_Resume.pdf`

## Mocks

`mocks/` holds the design explorations — `theme-directions.html` (four themes, switchable) and
`signal.html` (the chosen direction). Neither is needed to run the site.

## Contact

**Sumukh P Marathe**

- sumukhmarathesonda@gmail.com
- +91 82177 39781
- [LinkedIn](https://linkedin.com/in/sumukh-marathe-170732263)
- [GitHub](https://github.com/Sumukh2003)
