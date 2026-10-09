# Source Register

**Purpose:** Master index of research sources. This is a living bibliography, not a list of conclusions.

## Status legend

- **Collected** — source artifact is archived in this repository.
- **Referenced** — canonical source identified and used/reviewed, but a local archival copy is not yet stored.
- **Pending** — source identified as useful but not yet reviewed.
- **Rejected** — considered and rejected, with reason recorded.

| ID | Source | Type | Year | Status | Primary relevance |
|---|---|---|---:|---|---|
| SRC-001 | UNESCO, *Reimagining our futures together: A new social contract for education* | International commission report | 2021 | Collected | Purpose and future of education; education as a public/common good; alternative futures |
| SRC-002 | OECD, *Learning Compass 2030: A Series of Concept Notes* | Framework / concept notes | 2019 | Referenced | Future-oriented goals, knowledge, skills, attitudes, values, student agency |
| SRC-003 | OECD, *The OECD Learning Compass 2030* | Framework webpage | Current | Referenced | Current official description and local contextualisation principle |
| SRC-004 | UNICEF, *Every child learns: Education Strategy 2019–2030* | Strategy | 2019 | Collected | Learning outcomes, life/work/citizenship, system transformation |
| SRC-005 | UNICEF, *Education Strategy 2026: Shaping the Future of Learning* | Strategy | 2026 | Collected | Current global education priorities, learning, equity and skills |
| SRC-006 | World Bank, *Bangladesh Learning Poverty Brief* | Country evidence brief | 2024 | Collected | Bangladesh learning outcomes and system context |
| SRC-007 | Bangladesh Ministry of Education, *National Education Policy 2010* | National policy | 2010 | Collected | Bangladesh's stated aims, principles and system goals |
| SRC-008 | World Bank, *Global Education Policy Dashboard* | Measurement framework / report | 2026 | Collected | Evidence-informed system conditions and policy bottlenecks |
| SRC-010 | Stanford Encyclopedia of Philosophy, “Philosophy of Education” | Scholarly reference article | Current edition | Referenced | Nature and aims of education; philosophical distinctions and competing purposes |
| SRC-011 | UNESCO Institute for Statistics, *International Standard Classification of Education (ISCED 2011)* | International statistical classification | 2012 | Referenced | Operational definitions of education programmes and learning; international comparability |

## Initial source-selection observation

The source base mixes international normative work, future-oriented frameworks, child-focused system strategy, country-level evidence, Bangladesh policy, system measurement, scholarly philosophy, and international statistical classification. This variety helps frame the questions, but it does not by itself guarantee a balanced evidence base. Critical scholarship and counterevidence must still be actively sought.

## Archival status

The following original source files are currently present in the repository:

- `sources/documents/SRC-001-unesco-reimagining-our-futures-together-2021.pdf`
- `sources/documents/SRC-004-unicef-every-child-learns-2019.pdf`
- `sources/documents/SRC-005-unicef-shaping-the-future-of-learning-2026.pdf`
- `sources/documents/SRC-006-world-bank-bangladesh-learning-poverty-brief-2024.pdf`
- `sources/documents/SRC-007-bangladesh-national-education-policy-2010.pdf`
- `sources/documents/SRC-008-world-bank-global-education-policy-dashboard-2026.pdf`

The OECD concept-note PDF for SRC-002 has not yet been archived. SRC-010 is a web reference article and SRC-011 is an official classification document currently referenced by its canonical URL. Their step-specific records are stored in `sources/phase-01/step-02/`.

## Additional data archive

The World Bank Learning Poverty Global Database is present at:

`data/phase-01/SRC-006-world-bank-learning-poverty-database-2024.xls`

The repository file is an `.xls` workbook, not `.xlsx`. Preserve the actual format unless the file is deliberately converted and the conversion is documented.

## Archival rules

- Do not rename a source downloaded from an official provider into a different document or merge multiple source documents into one PDF.
- One source ID should correspond to one identifiable source artifact unless the provider itself publishes a series as separate files.
- If a provider publishes a source only as a webpage and no official downloadable document exists, do not create a PDF by printing the webpage. Record it as a web source instead.
- A source being archived does not mean its claims have been fully reviewed or accepted.
