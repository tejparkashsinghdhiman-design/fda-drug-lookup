# MoleculeScope

An educational, 18+ drug chemistry and interaction explorer. Single-file static web app — no build step, no server, no API keys required.

## Features

- Chemistry via PubChem (MW, LogP, TPSA, HBD/HBA, SMILES, InChIKey) with RDKit-rendered 2D structures in a Web Worker
- Pharmacology via ChEMBL (mechanism of action, targets, clinical phase) with structural fallback through UniChem
- Safety via openFDA (contraindications, warnings, drug interactions, FAERS adverse events)
- Drug–drug interaction checker with RxNorm brand-to-generic normalization and honest "unverified" states
- UniChem cross-references (ChEMBL, DrugBank, ChEBI, RCSB PDB, 20+ sources)
- UniChem connectivity search (salts, stereoisomers, mixtures)
- Search history persisted in localStorage (15 entries, deduplicated, removable)
- 18+ age gate (hard modal, remembered)

## Deploy

1. Create a public GitHub repo
2. Upload `index.html`, `README.md`, `LICENSE`, `.nojekyll`
3. Settings → Pages → Source: Deploy from a branch → `main` → `/ (root)` → Save
4. Site deploys in ~1 minute

**Note:** `.nojekyll` is required. Without it GitHub Pages runs Jekyll and the deploy will silently 404.

## Disclaimer

Educational use only. Not medical advice. 18+ only. Verify everything with official labeling and a licensed clinician.

## License

MIT — see `LICENSE`.
