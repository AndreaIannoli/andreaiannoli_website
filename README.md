# Andrea Iannoli - Hugo Website

This repository contains a Hugo site using the `hugo-toigian` template.

## Run locally

1. Install Hugo Extended (v0.93+ recommended).
2. Install theme dependencies (already done once in this repo):

```bash
cd themes/hugo-toigian
npm install
cd ../..
```

3. Start development server:

```bash
hugo server -D --disableFastRender
```

## Build production site

```bash
hugo --environment production --minify
```

Output will be generated in `public/`.
