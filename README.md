# Jerad XYZ (Hugo)

Your original `jerad.xyz` design and content, rebuilt as a Hugo static site. Same look — `styles.css` and `media/` are untouched — but pages are now generated from markdown instead of hand-written HTML.

## Add a new post, project, poem, or photo/illustration note

1. Duplicate any file in the matching folder:
   - `content/writing/`
   - `content/projects/`
   - `content/poems/`
   - `content/visuals/photos/`
   - `content/visuals/illustrations/`
2. Give it a new filename — that becomes the URL, e.g. `content/writing/my-new-post.md` → `/writing/my-new-post/`.
3. Fill in the frontmatter at the top:

```yaml
---
title: "My New Post"
date: 2026-09-01
tags: ["surf", "faith"]
summary: "One or two sentences shown in the list view."
image: ""        # optional, e.g. /media/photos/my-photo.jpg
image_alt: ""    # optional
---
```

4. Write the body underneath the `---`. Plain markdown or raw HTML both work.
5. Rebuild: `hugo --gc --minify`. This regenerates the whole `public/` folder from scratch — nothing to touch by hand.

## Add a whole new section (e.g. "Music")

1. Make a folder: `content/music/`.
2. Add an `_index.md` inside it for the section's own hero copy:

```yaml
---
title: "Music"
description: "Songs and demos by Jerad Acosta."
page_heading: "Songs and demos"
page_subhead: "One line describing the section."
---
```

3. Add entries the same way as any other section (step above).
4. Run `hugo` — the list page and detail pages exist immediately, using the same design as Writing/Projects. Linking to it from the homepage or nav is optional and is a small edit to `content/_index.md` (the `paths`/`features` list) and `layouts/_default/baseof.html` (the nav links) when you're ready to make it public-facing.

## Local preview

```
hugo server
```

Opens a live-reloading local copy at `http://localhost:1313`.

## Build for production

```
hugo --gc --minify
```

Outputs the full static site to `public/` — this is what gets deployed.

## Deploy

`netlify.toml` is already set up: build command `hugo --gc --minify`, publish directory `public`. Point Netlify at this repo (or run `netlify deploy --build --prod` after linking the site) and every push rebuilds automatically.

## What didn't change

- `static/styles.css` is your original stylesheet, copied over as-is.
- `static/media/` is your original media folder, copied over as-is.
- The homepage, writing list/detail, and project list/detail pages all render from the same copy and layout as the current live site — just as Hugo templates (`layouts/`) instead of duplicated HTML.

## What's new but not yet linked publicly

`content/poems/`, `content/visuals/photos/`, and `content/visuals/illustrations/` are wired up and buildable (matching the README structure from the original repo) but have no entries yet and aren't linked from the nav or homepage. Add content whenever you're ready — the section already works.
