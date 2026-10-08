# Source Register

**Purpose:** Master index of research sources. This is a living bibliography, not a list of conclusions.

## Status legend

- **Collected** — source document is archived in this repository.
- **Referenced** — canonical source identified and used/reviewed, but a local archival copy is not yet stored.
- **Pending** — source identified as useful but not yet reviewed.
- **Rejected** — considered and rejected, with reason recorded.

| ID | Source | Type | Year | Status | Primary relevance |
|---|---|---|---:|---|---|
| SRC-001 | UNESCO, *Reimagining our futures together: A new social contract for education* | International commission report | 2021 | Referenced | Purpose and future of education; education as a public/common good; alternative futures |
| SRC-002 | OECD, *Learning Compass 2030: A Series of Concept Notes* | Framework / concept notes | 2019 | Referenced | Future-oriented goals, knowledge, skills, attitudes, values, student agency |
| SRC-003 | OECD, *The OECD Learning Compass 2030* | Framework webpage | Current | Referenced | Current official description and local contextualisation principle |
| SRC-004 | UNICEF, *Every child learns: Education Strategy 2019–2030* | Strategy | 2019 | Referenced | Learning outcomes, life/work/citizenship, system transformation |
| SRC-005 | UNICEF, *Education Strategy 2026: Shaping the Future of Learning* | Strategy | 2026 | Referenced | Current global education priorities, learning, equity and skills |
| SRC-006 | World Bank, *Bangladesh Learning Poverty Brief* | Country evidence brief | 2024 | Referenced | Bangladesh learning outcomes and system context |
| SRC-007 | Bangladesh Ministry of Education, *National Education Policy 2010* | National policy | 2010 | Referenced | Bangladesh's stated aims, principles and system goals |
| SRC-008 | World Bank, *Global Education Policy Dashboard* | Measurement framework | 2026 | Referenced | Evidence-informed system conditions and policy bottlenecks |

## Initial source-selection observation

The first source set deliberately mixes:
- international normative work (UNESCO);
- future-oriented frameworks (OECD);
- child-focused system strategy (UNICEF);
- country-level evidence (World Bank);
- Bangladesh's own policy commitments (Ministry of Education);
- system measurement infrastructure (World Bank).

This prevents Step 1 from being defined only by one institution's philosophy.

## Archival queue

The following documents should be copied into `sources/documents/` when direct archival transfer is available:

- SRC-001 — UNESCO 2021 full report
- SRC-002 — OECD Learning Compass concept-note series
- SRC-006 — Bangladesh Learning Poverty Brief 2024
- SRC-007 — Bangladesh National Education Policy 2010
- SRC-005 — UNICEF Education Strategy 2026

Until then, their official/canonical records above are the authoritative references.


## Archive filenames to be supplied manually

When the original files are available, place them exactly as follows:

| Source ID | Repository path | Expected file |
|---|---|---|
| SRC-001 | `sources/documents/SRC-001-unesco-reimagining-our-futures-together-2021.pdf` | UNESCO 2021 full report |
| SRC-002 | `sources/documents/SRC-002-oecd-learning-compass-2030-concept-notes.pdf` | OECD Learning Compass concept-note series / official compiled PDF if available |
| SRC-004 | `sources/documents/SRC-004-unicef-every-child-learns-2019.pdf` | UNICEF Education Strategy 2019–2030 full report |
| SRC-005 | `sources/documents/SRC-005-unicef-shaping-the-future-of-learning-2026.pdf` | UNICEF Education Strategy 2026 |
| SRC-006 | `sources/documents/SRC-006-world-bank-bangladesh-learning-poverty-brief-2024.pdf` | World Bank Bangladesh Learning Poverty Brief 2024 |
| SRC-007 | `sources/documents/SRC-007-bangladesh-national-education-policy-2010.pdf` | Bangladesh National Education Policy 2010 |
| SRC-008 | `sources/documents/SRC-008-world-bank-global-education-policy-dashboard-2026.pdf` | Official dashboard report/export if an archival PDF is available |

### Additional data archive

For the quantitative Bangladesh learning-poverty evidence, also collect the official dataset:

`data/phase-01/SRC-006-world-bank-learning-poverty-database-2024.xlsx`

Source metadata: World Bank Learning Poverty Global Database, 2024 release.

### Important

Do not rename a source downloaded from an official provider into a different document and do not merge multiple source documents into one PDF. One source ID should correspond to one identifiable source artifact unless the provider itself publishes a series as separate files.

If a provider publishes a source only as a webpage and no official downloadable document exists, do **not** create a PDF by printing the webpage. Record it as a web source instead.
