# Blog Demo

A demonstration blog application powered by [blog-engine](../blog-engine).

## What is this?

This is a **minimal, auto-generated demo** that showcases the blog-engine system. It contains:

- Auto-generated sample content created by `blog-engine init`
- Minimal configuration
- Complete build setup for converting Markdown to HTML

## Purpose

This demo serves as:
- A **reference implementation** showing how to use blog-engine
- A **starting point** for creating your own blog
- A **test environment** for blog-engine development

## Quick Start (Standalone)

1. Install dependencies:
   ```bash
   npm install
   ```

2. Initialize (if not already done):
   ```bash
   npm run init
   ```

3. Process posts and start dev server:
   ```bash
   npm run process
   npm run dev
   ```

## Available Scripts

- `npm run init` - Initialize blog structure (already done)
- `npm run process` - Convert Markdown to JavaScript module
- `npm run dev` - Start development server
- `npm run build` - Build static site
- `npm run preview` - Preview built site

## Structure

```
blog-demo/
├── content/
│   └── posts/
│       └── welcome.md          # Sample post (auto-generated)
├── blog.config.js              # Blog configuration
├── package.json                # Dependencies
└── README.md                   # This file
```

## Creating Your Own Blog

To create your own blog based on this demo:

1. Create a new directory for your blog
2. Install blog-engine: `npm install blog-engine`
3. Initialize structure: `npx blog-engine init`
4. Replace sample posts with your own content in `content/posts/`
5. Customize `blog.config.js` with your blog details
6. Process and run: `npx blog-engine process && npx blog-engine dev`

## Deployment

This demo includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and deploys to GitHub Pages when you push to the main branch.

## License

MIT
