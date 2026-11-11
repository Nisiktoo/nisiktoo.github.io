# Mahfuz Bin Minhaz portfolio prototype

This is a clean Astro-based personal portfolio prototype designed to be easy to extend into a real portfolio, blog, or project showcase.

## Structure

```text
/
├── public/
├── src/
│   ├── components/
│   ├── data/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── package.json
├── README.md
└── tsconfig.json
```

## Commands

```bash
npm install
npm run dev
npm run build
npm run preview
```

## How this prototype is set up

- Reusable layout and navigation shell
- Data-driven content for projects, skills, achievements, and blog snippets
- Responsive landing page designed for a developer portfolio
- Simple section structure meant to be extended without rewriting the whole site

## Extend it

- Update `src/data/site.ts` with your actual content
- Add more project cards or blog entries in the same structure
- Add real pages under `src/pages/`
- Replace the placeholder phrase and social links with your own details
