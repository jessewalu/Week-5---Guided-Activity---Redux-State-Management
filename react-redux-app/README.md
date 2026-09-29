## Run the app

Open a terminal in this folder (`react-redux-app`) and run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite, usually `http://localhost:5173/`.

Do not launch this project with Five Server or by opening `index.html` directly. React's TypeScript entry point needs Vite to transform and serve it.

## Check the production build

```bash
npm run build
```

## Counter state

The counter actions and reducer live under `src/store/`. The Redux store combines the reducer and enables `redux-logger`; `src/main.tsx` makes the store available to the app with React-Redux's `Provider`.
