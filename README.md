# HandConnect

A static hand-tracking AR demo built with MediaPipe Hands and Web Audio API.

## Run locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the local server:
   ```bash
   npm start
   ```
3. Open the browser at `http://localhost:3000`

## Deploy to GitHub Pages

This project is deployable as a static site.

1. Make sure your repository remote is set to your GitHub repo.
2. Run:
   ```bash
   npm run deploy
   ```

The site will publish to the GitHub Pages URL configured in `package.json`.

## Notes

- The project is a static HTML app, so no build step is required.
- `node_modules` is ignored and should not be committed.
