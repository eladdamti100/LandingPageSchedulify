# Schedulify Landing Page

Marketing landing page for the **Schedulify 4.0** desktop application.

This is a completely static site: plain `index.html` plus assets, designed to be deployed on Vercel.

## Project structure

- `index.html` – main landing page (all styling is inline in a `<style>` block)
- `assets/` – images and demo video used by the page
- `styles.css` – older experimental styles (not currently referenced by `index.html`)

## Running locally

No build step is required.

1. Open `index.html` directly in your browser, or
2. Serve the folder with any static file server, for example:

   ```bash
   # From the landing folder
   npx serve .
   ```

## Deploying to Vercel

1. Push this repository to GitHub (for example `eladdamti100/LandingPageSchedulify`).
2. Go to `https://vercel.com`, click **Add New → Project**, and choose this GitHub repo.
3. In the project settings:
   - **Framework preset**: `Other`
   - **Root directory**: `/` (the repo root)
   - **Build command**: leave empty (no build step)
   - **Output directory**: `.` (current directory)
4. Click **Deploy** – Vercel will build and host the static site from `index.html`.

> **Note:** The download and documentation links in the footer assume that you will either:
> - Upload the installer archive (e.g. `Schedulify.zip`) to the project root, or
> - Point those links to an external location (such as a GitHub Release or other hosting).

