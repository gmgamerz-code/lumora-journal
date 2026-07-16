# Lumora Journal

A cinematic, professional blog website for Lumora Pictures.

Turkish drama meets Pakistani soul — stories that linger.

## Live Site

After enabling GitHub Pages, your site will be live at:

`https://gmgamerz-code.github.io/lumora-journal`

## Features

- Elegant dark cinematic design with warm gold accents
- Fully responsive (mobile-first)
- Live search + category filters
- Beautiful reading experience in modal
- Reading progress bar
- Share buttons (Twitter/X, LinkedIn, Copy link)
- Newsletter signup with nice feedback
- Easy to customize and extend

## How to Customize

### Add New Posts
Edit the `posts` array in `index.html` (JavaScript section). Each post is an object with:
- `id`
- `title`
- `excerpt`
- `category` (Behind the Scenes, Culture, Craft, Storytelling, etc.)
- `date`
- `readTime`
- `image` (use high-quality image URL)
- `tags`
- `content` (HTML supported)

The site automatically updates the UI.

### Change Images
Replace the `image` URLs in the posts array or use your own AI-generated images.

### Branding
- Logo text is in the navbar (easy to change)
- Colors are controlled via Tailwind + a few custom CSS variables

## Deployment (GitHub Pages)

1. Go to your repo **Settings** → **Pages**
2. Set **Source** to `Deploy from a branch`
3. Choose branch: `main` and folder: `/ (root)`
4. Save
5. Wait 1-2 minutes

Your site is now live!

## Local Development
Just open `index.html` in any browser. No build step needed.

## Tech Stack
- Pure HTML + Tailwind CSS (CDN)
- Vanilla JavaScript
- Zero dependencies
- Lightning fast

## Next Level Upgrades (Optional)
- Move to Astro or Next.js for better SEO & CMS
- Add real comments with Giscus or Utterances
- Connect a headless CMS (like Sanity or Contentful)
- Add your actual YouTube embeds

---

Built with care for Lumora Pictures.

Stories that linger. Emotions that stay.