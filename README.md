# Pokedex

A minimal, fast Pokédex web app built with Vite and React. This project provides a searchable list of Pokémon, detail pages with stats and evolutions, and a responsive UI styled with SCSS.

## Features

- Search Pokémon by name
- Paginated / lazy-loaded list of Pokémon
- Pokémon detail pages with images, stats, resistances and evolution chain
- Lightweight client-side state management with reducers and middlewares
- Responsive layout and SCSS-based styling

## Tech stack

- Vite
- React (JSX)
- SCSS for styling
- Client-side store (reducers + middlewares)
- Fetches data from the public PokéAPI (https://pokeapi.co/) by default

## Prerequisites

- Node.js (LTS recommended)
- npm or yarn

## Install

Open a terminal and run:

```powershell
npm install
```

## Development

Start the development server (hot reload):

```powershell
npm run dev
```

The app will be served by Vite (usually at `http://localhost:5173`).

## Build

Create an optimized production build:

```powershell
npm run build
```

Preview the production build locally:

```powershell
npm run preview
```

## Project structure (key files)

- `src/` — main source folder
	- `main.jsx` — application entry
	- `components/` — React components (App, Home, Cards, PokemonDetails, etc.)
	- `store/` — store initialization
	- `reducers/` — reducers for app state
	- `middlewares/` — custom middlewares for async/data flow
	- `actions/` — action creators and types
	- `styles/` — global SCSS files and variables

## Environment / API

The app is set up to fetch Pokémon data from the public PokéAPI. If you need to proxy or use a different backend, update the data fetching logic found in `src/actions` / `src/middlewares`.

## Contributing

Contributions are welcome. A simple suggested flow:

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/example`)
3. Make changes and add tests where appropriate
4. Open a pull request describing your changes

Please ensure code follows the project's style (SCSS + JSX patterns) and that UI remains responsive.

## Troubleshooting

- If styles are not applied, ensure Node modules are installed and Vite is running.
- If API requests fail, check your network and any CORS/proxy configuration.

## License

No license file is included in this repository. If you want to add a license, create a `LICENSE` file (for example, the MIT license) or consult the repository owner.

## Contact

Repository: `SlimDumbledodge/Pokedex`

If you want help running or extending this project, open an issue or contact the repository owner.
