# Lester René — Portfolio Website

Official portfolio website of choreographer and dancer Lester René.

This is a cinematic editorial portfolio presenting selected choreographic works, press, ideas and artistic projects. The site is designed as a focused professional entry point for artistic directors, presenters, collaborators and cultural institutions.

Live site: [lesterrene.com](https://www.lesterrene.com/)

## About

Lester René is a Cuban-born choreographer and dancer based in Germany. His work moves between contemporary dance, physical theatre and visually driven stage work.

The website presents his artistic profile, selected works, collaborators, press quotes, editorial ideas and contact information.

## Selected Works

Featured works include:

- `Casita`
- `Saturn Return`
- `Quantum Leap`
- `From the Lighthouse`
- `Shockheaded Peter`
- `Momo`
- `Im Osten was Neues`

## Press & Ideas

The site includes selected press references and a dedicated editorial space for public writing and cultural thinking, including Lester René's guest authorship for the NWZ series `50 Visionen für Oldenburg`.

## Tech Stack

- Static HTML
- CSS
- Vanilla JavaScript
- Local optimized image assets
- YouTube embeds loaded on interaction

No framework or build step is required.

## Deployment

The production site is deployed on Cloudflare Pages.

Cloudflare Pages settings:

- Build command: none
- Output directory: `/`
- Deployment platform: Cloudflare Pages
- Custom domain: `lesterrene.com`

Environment variables:

- None required for the current static site.

The included `wrangler.jsonc` is a static assets configuration for Cloudflare-related tooling. It does not contain secrets.

## Local Development

Open `index.html` directly in a browser, or serve the folder with a simple static server:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## License

Source code is released under the MIT License.

All images, videos, texts, choreography documentation, press materials and artistic content remain All Rights Reserved by Lester René González Álvarez and the respective photographers, collaborators, theatres, publications and rights holders.
