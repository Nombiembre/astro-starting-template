# Astro Staring Template

This is a blank canvas template for developing with Astro, equipped with ESLint, Prettier, TypeScript, and TailwindCSS pre-configured to streamline your setup.

## Features

- **TypeScript** - Static typing and better developer tooling.
- **ESLint** - Linting configured with ESLint and TypeScript support.
- **Prettier** - Code formatting for consistent style.
- **TailwindCSS** - Utility-first CSS framework for easy styling.

## Getting Started

1. **Clone the repository:**

```sh
  git clone git@github.com:Nombiembre/astro-starting-template.git
  cd astro-starting-template
```


## 🧞 Scripts

```sh
    "dev": "astro dev",
    "start": "astro dev",
    "build": "astro build",
    "preview": "astro preview",
    "astro": "astro",
    "check": "npm run check:astro && npm run check:eslint && npm run check:prettier",
    "check:astro": "astro check",
    "check:eslint": "eslint .",
    "check:prettier": "prettier --check .",
    "fix": "npm run fix:eslint && npm run fix:prettier",
    "fix:eslint": "eslint --fix .",
    "fix:prettier": "prettier -w ."
```
