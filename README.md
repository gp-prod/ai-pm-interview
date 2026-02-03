# AI PM Interview Practice

## Running the app

### Option A: Static preview (no npm required)
The repository includes a prebuilt static preview at `dist/index.html`.
You can serve it from the repository root:

```bash
python -m http.server 4173
```

Then open:

```
http://localhost:4173/dist/
```

### Option B: Vite dev server (requires npm registry access)
If npm registry access is available:

```bash
npm install
npm run dev
```

Then open the URL shown in the Vite output (typically `http://localhost:5173`).

If `npm install` fails with a 403 error, the environment is blocking npm registry access.
In that case, use Option A or configure npm to use an approved registry.
