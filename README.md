# lra-volume-v

**Volume V: Modern Analysis** — Overleaf-ready standalone repository.

## Structure

```text
volume-v.tex          — full-volume root (Overleaf main document)
volume-v-<book>.tex   — individual book roots
common/               — shared LaTeX infrastructure supplied by lra-common; ignored here
bibliography/         — per-book bibliography shards
volume-v/             — all LaTeX content for this volume
```

## Overleaf

Upload or checkout `common/` beside this repository's TeX roots, then set the main document to `volume-v.tex` for the full volume or to one of the book roots:

```text
volume-v-complex-analysis.tex, volume-v-functional-analysis.tex, volume-v-measure-theory.tex, volume-v-probability.tex
```

`common/` is ignored by git in this volume repo; edit shared infrastructure in `lra-common`.

## Building locally

```powershell
python F:\repos\lra-governance\tools\governance\build_volume_docker.py --root F:\repos\lra-volume-v --common-root F:\repos\lra-common
```
