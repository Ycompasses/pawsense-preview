# PawSense

PawSense mobile frontend preview · React + TypeScript + Vite.

Preview: https://ycompasses.github.io/pawsense-preview/

The complete frontend source and original design assets are stored in sixteen archive parts. GitHub Actions joins them, extracts the source and builds the site.

```sh
cat pawsense-source.zip.part* > source.zip
unzip source.zip -d frontend
cd frontend
npm ci
npm run dev
```

Authentication, camera capture and checkout are frontend demonstrations.
