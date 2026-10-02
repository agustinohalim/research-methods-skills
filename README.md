# research-methods-skills

A Claude Code plugin with two research-methods skills, copied from
[K-Dense scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
and kept separate from writing procedures in
[academic-writing-skills](https://github.com/agustinohalim/academic-writing-skills).

| Skill | What it does |
|---|---|
| `neurokit2` | Reproducible NeuroKit2 workflows for physiological signals: data contract before processing, ECG cleaning and R-peak correction, duration-gated HRV, EDA decomposition, epochs and multimodal alignment. Local-only helper scripts. Not for diagnosis or device validation. |
| `aeon` | Time-series machine learning with aeon: classification (ROCKET, InceptionTime), regression, clustering, forecasting, anomaly detection, segmentation, distances, and benchmark comparison. |

## Install

```text
/plugin marketplace add agustinohalim/research-methods-skills
/plugin install research-methods@research-methods-skills
```

Provenance, upstream commit, and local changes are in `NOTICE.md`. License: MIT (`LICENSE`).
