# Keychain QA Exercise

## Installation

```bash
npm run setup
```

Or manually:
```bash
npm install --ignore-scripts
git submodule update --init --recursive
cd react-redux-realworld-example-app && npm install --ignore-scripts && cd ..
NODE_OPTIONS=--openssl-legacy-provider npm rebuild sqlite3
```

## Running

```bash
npm run dev
```

- Frontend: http://localhost:4101
- Backend: http://localhost:3000
