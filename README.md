# Sværd og Trolddom – template

Minimal template til Sværd og Trolddom - Webgame baseret på bøgerne Sværd og Trolddom. Bygget med React, TypeScript, Vite og Tailwind CSS.

Guide til udvikling af siden findes på [kajsaaviaja.github.io](https://kajsaaviaja.github.io/)

## Forudsætninger

Du skal have **Node.js** installeret (inkluderer npm).

1. Gå ind på [nodejs.org](https://nodejs.org/)
2. Download og installer **LTS**-versionen til dit styresystem
3. Tjek at det er installeret korrekt ved at køre følgende i en terminal:

   ```bash
   node -v
   npm -v
   ```

   Der skal komme et versionsnummer frem for begge kommandoer.

## Hent koden (git clone)

1. Installer [Git](https://git-scm.com/downloads), hvis det ikke allerede er installeret
2. Tjek at det er installeret korrekt ved at køre følgende i en terminal:

   ```bash
   git --version
   ```

   Der skal komme et versionsnummer frem.

3. Åbn en terminal, og naviger til den mappe, hvor projektet skal ligge
4. Klon repositoriet:

   ```bash
   git clone https://github.com/kajsaaviaja/svaert-og-troldom-template.git
   ```

5. Gå ind i den nye mappe:

   ```bash
   cd svaert-og-troldom-template
   ```

## Kom i gang

```bash
npm install
npm run dev
```

Siden kører herefter på `http://localhost:5173`.

## Scripts

- `npm run dev` – starter udviklingsserveren
- `npm run build` – bygger produktionsversion
- `npm run lint` – kører ESLint
- `npm run preview` – forhåndsviser den byggede version lokalt

## Teknologier

- [React](https://react.dev/) 19
- [Vite](https://vite.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)
