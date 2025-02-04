# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## Available Scripts

In your project directory, you can run:

```bash
# Starts development server with Hot Module Replacement (HMR)
"dev": "vite",

# Builds production-optimized bundle for deployment
"build": "vite build",

# Lints code using ESLint rules
"lint": "eslint .",

# Previews production build locally before deployment
"preview": "vite preview"
```

### Key Differences
- `dev`: Development server with instant updates
- `preview`: Production preview of built assets
- Always run `build` before `preview` to test latest changes

# Running the project locally to develop and test

```bash
npm run dev
```

# Linting the project

```bash
npm run lint
```

# Building and previewing production build with minification and tree-shaking

```bash
npm run build && npm run preview
```