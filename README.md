# Open-Source Turkish TTS Survey -- Catalog

A descriptive-metadata catalog of the open-source Turkish text-to-speech
(TTS) landscape, accompanying the literature survey:

> Roxas, D. Q., & Bolat, A. *A Literature Survey on Open-Source Turkish
> Text-to-Speech: Datasets, Models, and Emotion.*

This repository is **descriptive metadata only**. It contains one record
per surveyed paper, dataset, and model, with the authors' verified
findings on size, licensing, documentation, architecture, and emotion
support, plus a pointer (repository ID and, where applicable, a full
40-character commit/revision hash) to each third-party resource hosted
elsewhere.

## What this is NOT -- no redistribution

This catalog **redistributes no audio, text, model weights, or derived
data**. Every entry is metadata plus a pointer to a resource hosted by a
third party. Each external resource remains subject to its own license and
terms; accessing any listed resource is the user's responsibility. The
`license` values in the catalog are the authors' **research findings** as
observed during the February-April 2026 search window -- not legal advice,
and not an assertion that any resource is lawfully licensed or safe to
redistribute. See `DATA_STATEMENT.md` for full provenance, scope, and
non-persistence notes.

## Files

| File | Description |
| --- | --- |
| `turkish_tts_survey_papers.csv` | One record per surveyed paper (and screening-stage out-of-scope records, flagged): venue, architecture, dataset/model availability, MOS, emotion support, notes. |
| `turkish_tts_survey_datasets.csv` | One record per surveyed dataset: size, sample rate, license findings, copyright concerns, usability assessment, notes. |
| `turkish_tts_references.csv` | Bibliographic reference list (surveyed works plus background architecture, linguistics, evaluation-metric, and emotional-TTS references). |
| `DATA_STATEMENT.md` | Data statement: what the artifact is, no-redistribution policy, license-finding caveats, provenance, and scope. |
| `LICENSE` | CC BY 4.0 license for the authors' catalog records (see Scope note). |
| `README.md` | This file. |

## Provenance

Commit/revision hashes for HuggingFace/GitHub resources, and their
associated access dates, record the upstream repository state at the
June-2026 finalization (access date 2026-06-05); `n/a` marks resources
with no applicable hash (e.g., Google-Drive-only, paywalled DOIs,
arXiv-version-only, books). The catalog's license and size assessments
reflect the February-April 2026 search window. Upstream repositories may
change, be gated, relicensed, or withdrawn; recorded hashes are a frozen
snapshot and are not guaranteed to resolve in the future. This is a
versioned, frozen release; corrections are issued via new versions /
erratum, not silent updates.

## Inclusion procedure

The criteria for which resources were surveyed, how they were screened,
and why out-of-scope records were retained-but-flagged are described in
the **Methodology section of the accompanying paper**. Please consult the
paper for the full inclusion/exclusion procedure.

## Citation

If you use this catalog, please cite both the paper and the catalog
deposit:

```
Roxas, D. Q., & Bolat, A. (2026). A Literature Survey on Open-Source
Turkish Text-to-Speech: Datasets, Models, and Emotion. [Catalog].
Zenodo DOI: to be minted on first release.
```

## License

The authors' catalog records and documentation in this repository are
licensed under **CC BY 4.0** (see `LICENSE`). This license covers only the
authors' own metadata records -- **not** the third-party resources the
catalog describes or links to, which each remain under their own separate
license and terms.

## Contact

Daniel Quillan Roxas (corresponding author) -- ORCID 0009-0000-4484-6751 (https://orcid.org/0009-0000-4484-6751); Ali Bolat -- ORCID 0009-0002-0488-2250 (https://orcid.org/0009-0002-0488-2250).