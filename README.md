# KAIROS_Public_Release

Repository: `sjasonprohaska/KAIROS_Public_Release` (personal account, public).

Kairos OS ∞, public release v0.1, by S. Jason Prohaska, 2025. The product brief in the repository reads: "Kairos OS is an ethical orchestration layer for AI systems that coordinates multiple AI components, workflow management, and compliance monitoring to enable responsible AI deployment within enterprise and institutional environments."

## Contents

| File | What it is |
|---|---|
| `kairos_core.py` | the public orchestration interface (Python 3.7 or later) |
| `kairos_clauses.md` | the twelve clauses, C-01 to C-12 |
| `karios_compliance_mapping.md` | references to ISO/IEC 42001, NIST AI RMF and the EU AI Act |
| `kairos_invocation_terms.md` | deployment terms and usage guidance |
| `kairos_manifest.json` | system state: Kairos OS 2.8 and its five modules |
| `kairos_product_brief.md` | the product overview |
| `kairos_public_release.md` | the full public release text |
| `Sovereign_Co-Creation_Agreement_v1.2.md` | commercial licensing terms |
| `LICENSE.txt` | CC BY-NC-ND 4.0 International |
| `readme.txt` | command-line documentation |
| `README.md` | this file |

## Run

```text
python3 kairos_core.py "Should we share patient data with insurance partners?"
```

The run prints the clauses it applied, a summary and its reasoning, and writes a Markdown digest to `output/`.

The live compliance mapping is on CodePen: https://codepen.io/S-Jason-Prohaska/live/xbwxJzP

## Licence

CC BY-NC-ND 4.0 International, licensed to the public by S. Jason Prohaska, 2025. It covers the documentation, sample outputs and invocation terms. Commercial use follows the Sovereign Co-Creation Agreement v1.2.

## Next step

Register action `PUBLIC_KEEP` in the personal account. The current README lists `digest_log_index.json`, `sample_trace.json` and `sample_digest.md`, and a `PY_stack/` folder; none is in the repository, and `kairos_core.py` sits at the root. The sidecar finds the three sample files on the Mac or records them as not found. The compliance mapping file keeps its name as committed. The clauses C-01 to C-12 are the source of the clause cards in the design system.

## Contact

https://contact.ethraeon.ai/

Copyright 2024-2026 ETHRAEON Systems.

Humanitas Ante Machinam.
