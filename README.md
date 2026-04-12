# HyperZoneLogin Website

The official website source for the HyperZoneLogin project.

This site is built with **Astro 6**, uses **Svelte** for interactive widgets, and is styled with **Tailwind CSS v4**.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Bun](https://bun.sh/)

### Local Development

```bash
bun install
bun run dev
```

By default, Astro serves the site on `http://localhost:4321`.

### Production Build

```bash
bun run build
bun run preview
```

## Project Focus

This website introduces HyperZoneLogin and its module ecosystem:

- proxy-layer login orchestration for Velocity
- official + third-party Yggdrasil authentication
- offline account support
- profile and skin handling
- migration tooling for legacy login plugins

Official documentation: https://docs.h2l.icu

## Main Directories

```text
src/pages/        Route pages
src/components/   Reusable UI and interactive islands
src/content/      News/updates content (MDX)
src/layouts/      Shared page layout
public/           Static assets
ref/HyperzoneLogin/  Reference project source and docs
```

The website links users to the external docs portal at `https://docs.h2l.icu` for setup and module guides.

## Content and Language

- Public-facing website content is written in English.
- Route compatibility pages are kept for older links.

## Contributing

Open issues or pull requests on the project repositories:

- https://github.com/HyperZoneLogin/HyperzoneLogin

## License

Website code is provided under the repository license in `LICENSE`.
