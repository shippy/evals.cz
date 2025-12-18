# Evals.cz

Website for Evals.cz - a Prague meetup focused on evaluating AI applications and production LLM systems.

## About

Evals.cz is a Prague-based meetup for people building or researching AI-powered products, with practical focus on evaluating RAG systems and LLM functionality in production environments.

## Tech Stack

- **Framework**: [Astro](https://astro.build) 5.x
- **Fonts**: Space Grotesk, JetBrains Mono
- **Styling**: Component-scoped CSS with global styles

## Project Structure

```text
/
├── public/
│   ├── favicon.svg
│   └── og-image.png
├── src/
│   ├── components/
│   │   ├── Hero.astro
│   │   ├── Topics.astro
│   │   ├── Audience.astro
│   │   ├── Format.astro
│   │   ├── Signup.astro
│   │   ├── Speaker.astro
│   │   └── Footer.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## Development

All commands are run from the root of the project:

```bash
# Install dependencies
yarn install

# Start dev server at localhost:4321
yarn dev

# Build production site to ./dist/
yarn build

# Preview production build locally
yarn preview
```

## Component Overview

The site is composed of modular sections:

- **Hero**: Landing section with main heading and CTA
- **Topics**: Overview of meetup topics (RAG, LLM evaluation, etc.)
- **Audience**: Target audience description
- **Format**: Meetup format and structure details
- **Signup**: Registration/signup section
- **Speaker**: Call for speakers with submission details
- **Footer**: Footer with links and information

## Design System

The site uses a brutalist-inspired design with:
- Color palette: Black, white, red accent (#D7141A), blue accent (#11457E)
- Bold borders (2px - 8px)
- Shadow effects for depth
- Monospace and display fonts
- No border radius (sharp, geometric aesthetic)

## License

MIT
