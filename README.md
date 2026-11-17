# Seyr

> **Note:** The source code of Seyr lives in a private repository. This public repo is a
> project overview: what Seyr is, what it does, and how it's built.

<p>
<a href="https://seyr.io/"><img src="https://img.shields.io/badge/Website-seyr.io-36BCF7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
</p>

**See where your visitors actually look.** Seyr is a lightweight behavior analytics and
recommendation service that drops into any site with a single script tag.

## Features

- **Tiny tracker:** ~3 KB, loads asynchronously, and records page views, click positions,
  scroll depth and how long each section stays on screen.
- **Privacy first:** never collects text, form values or keystrokes.
- **Heatmaps** for desktop, tablet and mobile.
- **Section attention:** a ranked list of the most viewed sections, down to individual rows.
- **Session recordings**, shipped as a separate bundle that only loads on sites where they're
  turned on.
- **Product recommendations:** from the products a visitor views, Seyr works out the
  categories they care about and recommends items they haven't seen yet.
- **Teams:** invite members to a site's dashboard.
- **GDPR & KVKK friendly:** consent mode, a retention period for raw data and a per-person
  delete API.

## Tech stack

| Layer | Technologies |
|---|---|
| Dashboard & site | Next.js, TypeScript |
| Backend | Convex |
| Tracker | Vanilla JS, async, ~3 KB |

## Status

Seyr is a personal project I built end to end, and it's live at [seyr.io](https://seyr.io/).
My own portfolio runs on it too. The source code is private. More on my site:
[semihsamandar.com/projects/seyr](https://www.semihsamandar.com/projects/seyr).
