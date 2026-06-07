# Kartik's Vault

A multi-disciplinary knowledge base and personal portfolio covering computer science fundamentals, distributed systems, financial economics, and behavioral science. Built as a version-controlled documentation site.

Live at [kartik-docs.mintlify.app](https://kartik-docs.mintlify.app).

## Structure

Content is organized into four top-level tabs, each with its own dashboard hub and a set of sub-topic modules:

- **Core CS** — foundations, assembly, competitive programming, operating systems, DBMS, networking
- **Systems** — system design, scaling, cloud infrastructure, Web2, Web3
- **Finance** — market fundamentals, tax planning, credit & leverage
- **Psychology** — human nature, dark psychology

Each sub-topic is its own folder with an `index.mdx` module landing page. Navigation and theming are configured in `docs.json`.

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run the dev server from the repo root (where `docs.json` lives):

```bash
mint dev
```

The preview is served at `http://localhost:3000`.

Useful checks before pushing:

```bash
mint validate        # validate the build
mint broken-links    # check internal links
```

## Publishing

Changes are deployed automatically when pushed to the default branch.

## Troubleshooting

- Dev server won't start: run `mint update` to get the latest CLI.
- A page 404s: confirm you're running from a folder with a valid `docs.json`.

## Contact

- GitHub: [thekartikwalia](https://github.com/thekartikwalia)
- LinkedIn: [thekartikwalia](https://www.linkedin.com/in/thekartikwalia/)
- X: [thekartikwalia](https://x.com/thekartikwalia)
- Email: business.kartikwalia@gmail.com
