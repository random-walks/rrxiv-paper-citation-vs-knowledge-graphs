# Citation graphs are not knowledge graphs

A survey-style comparison cataloguing six structural differences between citation graphs and knowledge graphs, proposing a typed-edge extension for the rrxiv claim graph — a demonstration paper in the [rrxiv](https://rrxiv.com) reference corpus.

**Read the published paper:** [rrxiv.com/papers/rrxiv:2605.00006](https://rrxiv.com/papers/rrxiv:2605.00006)

## What this demonstrates

A survey-style comparison that catalogues six structural differences between citation graphs and knowledge graphs and proposes a typed-edge extension for the rrxiv claim graph. Five claims — a compact example of a meta-research / position paper in the corpus.

## Build it locally

This repo was created from the [rrxiv-paper-template](https://github.com/random-walks/rrxiv-paper-template).

```bash
./scripts/build.sh          # tectonic → build/main.pdf
./scripts/extract-cir.sh    # rrxiv parse → build/main.cir.json
./scripts/verify.sh         # validate the CIR against the rrxiv schema
```

Install the `rrxiv` CLI used by these scripts:

```bash
pip install 'rrxiv>=0.2.1'
```

## License

Dual-licensed, matching the rest of the corpus:

- **Content** — the paper text and figures in `paper/`, plus `rrxiv-meta.json`, under [CC-BY-4.0](./LICENSE-CONTENT).
- **Code** — the `scripts/` and CI under [MIT](./LICENSE-CODE).
