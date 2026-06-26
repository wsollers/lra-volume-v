# Volume Bibliography

This directory is owned by `lra-volume-v`.

Bibliography shards are book-owned and used directly by this volume repository. They are not copied to a monorepo or to `lra-common`.

Current shards:

- `volume-v-complex-analysis.bib`
- `volume-v-functional-analysis.bib`
- `volume-v-measure-theory.bib`
- `volume-v-probability.bib`

Add entries only to the shard for the owning book root, then run:

```powershell
python scripts/check_bibliography.py --bib-dir bibliography
```

Do not add unrelated volume bibliography files here.
