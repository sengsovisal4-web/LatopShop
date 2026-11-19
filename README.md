# Beyond Laptop — Frontend Demo

Angular 18 storefront prototype for the Beyond Laptop project.

## Run locally
```bash
cd frontend
npm install
npm start
``
Open http://localhost:4200.

The UI uses sample laptop data when the Spring Boot API at `http://localhost:8080/api/products` is unavailable.

## Deploy to Vercel
Import this repository into Vercel and set **Root Directory** to `frontend`.
- Framework Preset: Angular
- Build Command: `npm run build`
- Output Directory: `dist/beyond-laptop/browser`

The root `vercel.json` provides SPA route fallback. This deployment contains only the frontend demo; backend and database are not deployed.