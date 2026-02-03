# AI PM Interview Practice

## Run the app

### Option A: Static preview (no npm required)
The repository includes a prebuilt static preview in `dist/index.html`. You can serve it with any static server.

```bash
python -m http.server 4173
```

Then open: `http://localhost:4173/dist/`.

### Option B: Vite dev server (requires npm registry access)
If your environment can access the npm registry (or a private mirror), install dependencies and start the dev server:

```bash
npm install
npm run dev
```

If you encounter `403 Forbidden` during `npm install`, configure npm to use an allowed registry:

```bash
npm config set registry <YOUR_ALLOWED_REGISTRY_URL>
```

