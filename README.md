# Adit Space

A simple space-themed launchpad for publishing Adit's early Python projects and creative writing.

## Editing the site

- Update the homepage in `index.html`.
- Add or replace mission cards in the `Code Missions` section.
- Add stories, poems, or reflections in the `Transmissions` section.
- Keep personal details private: first name only, no school name, no home location, and no public contact info unless a parent controls it.

## Deploying on Cloudflare Pages

1. In Cloudflare, open **Workers & Pages**.
2. Create a new **Pages** project from the GitHub repo.
3. Use these build settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `/`
4. After the first deploy, add the custom domain `aditspace.com` in the Pages project.

Because this is a static site, there is no install step or build step.
