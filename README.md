# HSUHK ITSC — IT & AV onsite support outsourcing: controlled document register

Static GitHub Pages site listing every issue round, the controlled document set and the full
change logs. Generated from the project folder; do not edit by hand.

Generated: 2026-11-13 13:08 HKT

## Contents

- `index.html` — overview, issue rounds, document register, references, status
- `changelog.html` — change log by issue round, by document, and by QA round
- `data/register.json` — machine-readable register
- `CHANGELOG.md` — the same change logs in Markdown

## Scope of what is published

This repository carries document-control metadata and change history only. The controlled
Word files and Markdown sources remain in the project folder; they are released to ITSC
through the issue packs.

## Regenerate

```
python build_site.py --project <project folder> --out <repo folder>
```
