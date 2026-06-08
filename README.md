# Creativ Energy documentation

Mintlify docs for Creativ Solar sales reps, deployed at [creativenergy.mintlify.app](https://creativenergy.mintlify.app).

## Structure

- `sales/` — field rep guides (workflow, Off-peak calculator, Won/Quoted outcomes)
- `mcp.mdx` — MCP endpoint for AI assistants
- `docs.json` — site navigation and branding

## Local preview

```bash
npm i -g mint
mint dev
```

Open [http://localhost:3000](http://localhost:3000).

## Publishing

Push to `main`. Mintlify deploys automatically when the GitHub app is connected.

Source copies are also kept in the frontend repo at `creativuk-app/new-frontend/mintlify/` — update both when content changes, or treat this repo as the publish source of truth.
