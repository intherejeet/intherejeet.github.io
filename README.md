# Inderjeet Singh's research website

The public site at https://intherejeet.github.io/ is built with Hugo and PaperMod.

## Edit

- `content/_index.md`: homepage, research profile, and selected work
- `content/publications/_index.md`: papers, preprints, benchmarks, and patent
- `assets/css/extended/custom.css`: typography and layout
- `hugo.toml`: site metadata and navigation

Publication titles link to public records. Keep preprints distinct from peer-reviewed papers. Do not add unpublished projects, private contact information, internal results, datasets, or CV files to this repository.

## Preview

Install Hugo Extended 0.147.7 or newer, then run:

```sh
hugo server
```

The GitHub Actions workflow builds and deploys the site after a push to `main`.
