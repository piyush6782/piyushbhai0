# AGENTS.md

## Architecture
A static, single-file site. There is no framework, package manager or build step. Netlify publishes the `public/` directory as it is (see `netlify.toml`).

## Key files
- `public/index.html`: the whole page, with CSS in a `<style>` block and the countdown/redirect logic in an inline `<script>`.
- `netlify.toml`: sets `public` as the publish directory and leaves the build command empty.

## Conventions and notes
- Keep the site dependency-free. Fonts and icons come from Google Fonts and the cdnjs Font Awesome CDN.
- The Telegram invite URL is duplicated in the CTA `href` and in `TARGET_URL`. Keep the two in sync.
- The countdown ring's circumference is computed from `r="38"`. If you change the circle radius, update the script to match.
