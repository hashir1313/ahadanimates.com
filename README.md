# Ahad Animates

3D Artist Portfolio — [ahadanimates.pages.dev](https://ahadanimates.pages.dev)

<a href="https://astro.build/">![Astro](.github/images/astro-icon.png)</a>
<a href="https://tailwindcss.com/">![Tailwind](.github/images/tailwind-icon.png)</a>
<a href="https://alpinejs.dev/">![Alpine js](.github/images/alpine-icon.png)</a>

Portfolio website for Abdul Ahad, a 3D artist specializing in cinematic 3D advertisements, product animations, and motion graphics. Built with [Astro](https://astro.build), styled with [Tailwind CSS](https://tailwindcss.com/), interactive with [Alpine.js](https://alpinejs.dev/) and [React](https://react.dev/), animated with [GSAP](https://gsap.com/).

---

## Features

- [x] Keystatic CMS (cloud-hosted) for managing portfolio, blog, pages, and global settings
- [x] Dynamic OG image generation
- [x] RSS feed
- [x] SEO (sitemap, robots.txt, meta tags)
- [x] GSAP animations
- [x] Contact form
- [x] WhatsApp widget

## Getting Started

1. `bun install`
2. `bun run dev`
3. Open [http://localhost:4321](http://localhost:4321)

### Other Commands

| Command | Description |
| --- | --- |
| `bun run build` | Build for production |
| `bun run preview` | Preview production build locally |
| `bun run wrangler:dev` | Dev server via Cloudflare Pages |

## CMS Management (Keystatic)

Access the admin dashboard at [`/keystatic`](/keystatic) (or `/admin` which redirects there).

### Content Types

| Type | Description |
| --- | --- |
| **Works** | Portfolio case studies — title, description, tags, cover image, external link, and Markdoc content |
| **Posts** | Blog posts — title, description, author, tags, cover image, and Markdoc content |
| **Pages** | Page content via a block-based Markdoc editor (homepage, about, contact, works, news) |
| **Authors** | Author profiles with name, avatar, and bio |
| **Global Settings** | Header navigation, footer content, and WhatsApp widget toggle |

Content is stored in the cloud — no local git commits needed for content updates.

For more information, see the [Keystatic documentation](https://keystatic.com/docs/introduction).

---

## Credits

Based on the [Mizar](https://github.com/majesticooss/mizar) template by [Majesticooss](https://github.com/majesticooss).
