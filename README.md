# Tejaswi Kunche — Personal Portfolio

A responsive dark-themed portfolio built with React, TypeScript, Vite and custom CSS.

## Quick start

```bash
npm install
npm run dev
```

Open the localhost URL shown in the terminal.

## Build

```bash
npm run build
```

## Personalize before publishing

1. **Resume:** Put your latest resume PDF at `public/resume.pdf`. The resume link is intentionally a placeholder until you add the real file.
2. **LinkedIn:** In `src/main.tsx`, set `PROFILE.linkedin` to your actual URL. It will then appear in the hero links.
3. **Project links:** Set `demo` and `repo` in the `projects` array to the correct URLs. NEXORA's live demo is already linked. Other project links are intentionally not invented.
4. **Project details:** Verify all claims, project descriptions, achievements, and academic details before publishing.
5. **Contact:** Edit `PROFILE.email` if needed.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, select **Add New → Project**, import the repository.
3. Framework preset: **Vite**; build command: `npm run build`; output directory: `dist`.
4. Deploy and copy your public URL into internship applications.

## Notes

- No backend or contact-form service is required. The contact button opens the user's email application.
- The site has accessible labels, a responsive navigation menu, and reduced-motion support.
- This is a portfolio *source-code project*, not a hosted website. Hosting requires deployment.
