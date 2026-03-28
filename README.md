# Xeno AI Website

Dies ist ein kleines, direkt deploybares React-Projekt mit Vite für die Website von **Xeno AI**.

## Lokal starten

```bash
npm install
npm run dev
```

## Produktions-Build

```bash
npm install
npm run build
```

Der fertige Build liegt danach im Ordner `dist`.

## Deployment mit Vercel

1. Dieses Projekt in ein neues GitHub-Repository hochladen.
2. Auf Vercel einloggen.
3. **Add New → Project** wählen.
4. Das GitHub-Repository importieren.
5. Vercel erkennt Vite in der Regel automatisch.
6. Auf **Deploy** klicken.

## Deployment mit Netlify

1. Dieses Projekt in ein GitHub-Repository hochladen.
2. In Netlify **Add new site → Import an existing project** wählen.
3. Das Repository verbinden.
4. Build command: `npm run build`
5. Publish directory: `dist`

## Inhalte anpassen

- Text und Struktur: `src/App.jsx`
- Design und Farben: `src/styles.css`
- Seitentitel und Meta-Tags: `index.html`
