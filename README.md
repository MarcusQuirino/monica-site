# Monica de Assis – Contact Site

A simple single-page contact site I made for my mother-in-law, Monica de Assis Cabrera, a psychologist and psychoanalyst in Porto Alegre, Brazil.

Live: https://monica-de-assis.vercel.app

## Features

- Profile photo, name and title ("Psicóloga e Psicanalista")
- Phone contact
- Office address
- Embedded Google Maps view of the office location
- Mobile-first layout with a dark gradient background

## Stack

- [Vite](https://vitejs.dev/) (plain `index.html`, no framework)
- [Tailwind CSS](https://tailwindcss.com/) via PostCSS + Autoprefixer
- TypeScript (used for `tsc` in the build step)
- Deployed on Vercel

## Local development

Requires [Bun](https://bun.sh/).

```sh
bun install
bun run dev      # start the Vite dev server
bun run build    # type-check and build to dist/
bun run preview  # preview the production build
```

### Environment

The project has a `MAPS_API_KEY` variable for the Google Maps Embed API, kept in a local `.env` file. Note that the map iframe in `index.html` currently has its key written directly in the URL rather than reading this variable.

## TODO

See [TODO.md](TODO.md).
