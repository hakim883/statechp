# State Checkpoint

A small React practice project demonstrating component state and
conditional rendering: a "Show it / Hide it" button toggles a profile card
(name, photo, bio, profession) in and out of view.

This is a learning exercise (bootstrapped with Create React App) used to
practice React class components, `this.state`, and `react-bootstrap` —
not client work.

## Tech stack

- **Frontend:** React 17 (class components)
- **UI:** react-bootstrap + Bootstrap 5
- **Tooling:** Create React App (`react-scripts`)

## How it works

- `src/App.js` holds a single stateful component (`state extends
  Component`) with `isShown` toggled by a Bootstrap `<Button>`.
- When shown, it renders a profile card with a name, image, bio, and
  profession pulled straight from component state.

## Running locally

### Prerequisites

- Node.js (LTS) and npm

### Setup

```bash
npm install
npm start      # starts the dev server at http://localhost:3000
```

### Build

```bash
npm run build   # production build in build/
```

### Tests

```bash
npm test
```

## Status

Practice project — kept as-is for portfolio history. Dependency versions
have been updated (`react-scripts` bumped to a maintained release) so it
installs and builds cleanly on modern Node.js.

## License

MIT — see [LICENSE](./LICENSE).
