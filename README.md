# Molley Documentation

User documentation for Molley — your all-in-one platform for research, product development, and growth.

## About This Documentation

This documentation is designed for end users of Molley, including:

- **Solo entrepreneurs** building their products
- **Product managers** managing features and roadmaps
- **Sales teams** tracking outreach and customers
- **Research professionals** capturing and synthesizing insights

## Documentation Structure

- **Getting Started** — Quick start guide, company setup, projects
- **Features** — Detailed guides for each Molley feature
- **AI Assistant** — How to use Molley AI effectively

## Tech Stack

- **Static Site Generator**: [VitePress](https://vitepress.dev/)
- **Runtime**: Node.js
- **Deployment**: GitHub Pages (automated via GitHub Actions)

## Development

### Setup

```bash
npm install
```

### Development Server

Start the development server on `http://localhost:5173`:

```bash
npm run docs:dev
```

### Production Build

Build the documentation for production:

```bash
npm run docs:build
```

Preview the production build:

```bash
npm run docs:preview
```

## Project Structure

```
.
├── .vitepress/
│   ├── config.mts          # VitePress configuration
│   └── theme/              # Custom theme (Molley colors)
├── public/                 # Static assets (logo)
├── guide/                  # Getting Started guides
├── features/               # Feature documentation
├── ai/                     # AI Assistant guides
├── index.md                # Home page
└── package.json            # Dependencies and scripts
```

## Theme

The documentation uses Molley's brand colors:

- **Primary**: `#019cca` (Cyan)
- **Accent**: `#f2206b` (Pink/Coral)
- **Success**: `#6bb172` (Green)
- **Warning**: `#fea807` (Amber)

## Deployment

Deployment is automated via GitHub Actions. On every push to `main`, the workflow:
1. Installs dependencies
2. Builds the VitePress site
3. Deploys to GitHub Pages

The site is available at: https://docs.molley.io

## Writing Documentation

VitePress uses Markdown with additional features:

- **Front matter**: Configure page layout and metadata
- **Vue components**: Embed interactive components
- **Code blocks**: Syntax highlighting with line numbers
- **Custom containers**: Info, warning, danger boxes

See the [VitePress documentation](https://vitepress.dev/guide/markdown) for more details.