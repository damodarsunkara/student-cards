# StudentCards 

Lightweight demo that displays student cards using TypeScript, HTML, and CSS.

**Quick overview**

- `src/index.html` — entry HTML
- `src/css/style.css` — styles
- `src/ts/app.ts` — TypeScript logic

**Prerequisites**

- Node.js (recommended v18+)
- npm (bundled with Node.js)

## Install

Open a terminal in the project root and install dependencies:

```powershell
npm install
```

## Available scripts

- `npm run test` — placeholder test script (default)
- `npm run format` — format source files using Prettier

You can run TypeScript compilation manually with:

```powershell
npx tsc
```

To serve the `src` folder during development you can use a static server, for example:

```powershell
npx serve src
```

## Formatting (Prettier)

This repo includes Prettier configuration (`.prettierrc`) and `.prettierignore`.

- Format all source files:

```powershell
npm run format
```

- (Optional) Add a format check script to fail CI when files are not formatted. If you want, I can add a `format:check` script and a GitHub Actions workflow.

## Project layout

- `package.json` — scripts and dependencies
- `tsconfig.json` — TypeScript configuration
- `src/` — HTML/CSS/TS source files
- `.prettierrc`, `.prettierignore` — formatting configuration

## Development tips

- Run the Prettier formatter before committing to keep consistent style:

```powershell
npm run format; git add .; git commit -m "chore: format code with Prettier"
```

- If you'd like, I can add an npm `watch` or `build` script for TypeScript and a simple CI workflow.

## Contributing

- Feel free to open issues or PRs. Keep changes small and run `npm run format` before submitting.

---

If you'd like, I can:

- add a `format:check` npm script and a GitHub Actions workflow to run it on PRs,
- or add `build`/`watch` scripts for TypeScript compilation.
Reply which option you prefer and I'll add it.
