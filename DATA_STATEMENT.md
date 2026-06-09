# Data Statement — Open-Source Turkish TTS Survey Catalog

*Draft accompanying "A Literature Survey on Open-Source Turkish Text-to-Speech: Datasets, Models, and Emotion" (Roxas & Bolat). To be deposited with the catalog manifest on Zenodo and cited from the paper.*

## What this artifact is
A **self-authored metadata catalog** of the open-source Turkish TTS landscape: one record per surveyed paper, dataset, and model, with our verified findings on size, licensing, documentation, architecture, and emotion support. Files: `turkish_tts_survey_papers.csv`, `turkish_tts_survey_datasets.csv`, `turkish_tts_references.csv`.

## What this artifact is NOT — no redistribution
We **redistribute no audio, text, model weights, or derived data**. Every entry is descriptive metadata plus a pointer (repository ID and, where applicable, a commit/revision hash) to a third-party resource hosted elsewhere. Accessing any listed resource is the user's responsibility, subject to that resource's own terms.

## License fields are audited findings, not endorsements
The "license" values are **our research findings as observed during the survey's search window (February–April 2026)** — i.e., what we observed in the resource's metadata, card, or `LICENSE` file, and where these disagree, the discrepancy itself. They are **not** legal advice, and inclusion of a resource is **not** an assertion that it is lawfully licensed or safe to redistribute. Where we note a likely misclassification (e.g., a declared CC-BY-SA that contains a NonCommercial component), that is a documented observation, not an accusation of intent.

## Provenance and non-persistence
Each **repository-hosted record is stamped with an ISO access date** (the `Access_Date` column) and, **where applicable, the full commit/revision hash** observed at that date. The hash column reads `n/a` for resources to which no commit/revision identifier applies — for example, Google-Drive-only deposits, paywalled or DOI-only publications, arXiv-version-only preprints, and books. Upstream repositories may change, be gated, relicensed, or withdrawn; recorded hashes capture state at capture time and are **not guaranteed to resolve** in the future.

These two kinds of metadata are anchored to **different points in time, and the catalog records both deliberately.** The **revision hashes and ISO access dates capture each repository's state at the June-2026 finalization** of this release. The **license and size assessments, by contrast, reflect what we observed during the February–April 2026 search window** in which the survey was conducted; we did not re-audit every license or recompute every size at finalization, so where an upstream resource was relicensed or resized between the search window and finalization, the license/size fields describe the search-window state while the hash/access-date fields describe the finalization state.

This catalog is a **frozen snapshot**; it documents what existed in this state in 2026 and will not be silently updated. Corrections are handled via versioned releases / erratum.

## Scope
The catalog covers resources surfaced by the search described in the paper's Methodology section. Out-of-scope records retrieved during screening (non-Turkish or non-TTS works) are retained but explicitly flagged and excluded from the survey counts.

## Citation
Please cite the paper and this catalog's Zenodo DOI (to be minted).

## Contact
Daniel Quillan Roxas (corresponding author) -- ORCID 0009-0000-4484-6751 (https://orcid.org/0009-0000-4484-6751); Ali Bolat -- ORCID 0009-0002-0488-2250 (https://orcid.org/0009-0002-0488-2250).
