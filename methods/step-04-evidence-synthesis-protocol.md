# Step 4 — Operational Evidence Synthesis Protocol

**Status:** Approved working method, 2026-10-09  
**Owner:** Md. Nafiz

## 1. Before searching
1. State the question and claim type: conceptual, normative, descriptive, association, causal, historical, comparative, mechanism/experience, or feasibility.
2. Before title-level synthesis, operationally define “preparing students for the future” and “preparing students to pass examinations” as multidimensional constructs. Record observable indicators, population, stage, subject, setting, time horizon, and what counts as a close match.
3. Decide whether full traceability is required. It is mandatory for title-level synthesis, major causal/comparative claims, national policy-status claims, load-bearing statistics, and major recommendations.

## 2. Search record
For every substantial search, capture platform/repository, date/time, exact query, language, filters/date range, hit count if available, screening decisions, selected source IDs, and saved export or dated capture where permitted. Store under `data/searches/YYYY-MM-DD/`. If an export is unavailable or prohibited, record why and preserve available metadata.

Starting points: ERIC first for English education research; Scopus/Web of Science where accessible; Google Scholar with logged queries and indexing caveats; RePEc for education economics; World Bank Open Knowledge Repository, UNESDOC, OECD iLibrary; and Bangladesh sources including BanglaJOL, CAMPE's *Education Watch*, BRAC Institute of Educational Development studies, BANBEIS statistics, NCTB/Ministry primary documents, university repositories, and dated archives of current-affairs reporting. This list is a starting point, not a claim of exhaustive coverage.

Search in Bangla and English when relevant. Preserve terms in both languages if meaning may diverge. For translated instruments, record the original language, version consulted, translator/process if known, and evidence of linguistic/cultural validation. Record systematic differences between the Bangla and English evidence bases.

## 3. Source appraisal
Every substantive source needs an SRC-### record under `sources/phase-NN/step-NN/` and an entry in `sources/source-register.md`. Capture exact title, author/organization, date/version, stable URL/identifier, access date, original language, source type, provenance, commissioner/funder, declared interests, methods/data, population/setting, measures, exact page/table/section, corrections/retractions, and limits.

Assess source fit relative to the claim. Record whether sources are independent or repeat the same dataset/statement. Consider publication bias, selective outcome reporting, non-publication of null/adverse results, and language/indexing bias. Gray literature is eligible, but must be appraised for provenance, methods, sponsorship, interests, and selective reporting.

## 4. Evidence table
Use `evidence/phase-01/step-04/evidence-table-template.md`. Separate source-reported findings from my interpretation. Do not pool incompatible outcomes; classify them by outcome type and report direction/uncertainty separately. Measurement incompatibility may itself reveal a field-level evidence gap.

## 5. “Established evidence” threshold
Use this label only if either (a) at least two independent lines of evidence converge, using distinct datasets, methods, or research groups as appropriate; or (b) one high-quality study closely matches the claim's construct, population, setting, and design; and a documented active search located no credible counterevidence that materially overturns it. The setting/population must share the causal features on which the claim depends. Major recommendations require the complete traceability chain. Several publications repeating one dataset do not count as independent evidence. Otherwise use a narrower label such as finding, expert judgment, limited/mixed evidence, hypothesis, or speculation.

## 6. Load-bearing statistics
Trace every load-bearing statistic to its original study, dataset, official table, or primary record. If the origin cannot be located, mark it **unverified at source**, name the earliest traceable citation, and do not use it as the foundation of a major conclusion. Repetition is not verification.

## 7. Devil's-advocate pass
For every high-impact conclusion, archive in the relevant `review-log.md`: the strongest credible opposing case; best supporting evidence; assumptions of my preferred interpretation; missing evidence; what would change/reverse the conclusion; and any external expert/practitioner comments. AI may help check consistency but cannot be the sole substantive reviewer.

## 8. Normative disagreement
State value premises, record the strongest counterarguments, explain the weights assigned to competing considerations, and apply Step 3's evaluation criteria. These structure judgement but do not eliminate it. If reasonable disagreement remains, preserve it in the decision record rather than presenting a preferred value weighting as an empirical finding.

## 9. Review type and synthesis
Consider a formal systematic review when the question is causal or comparative, a substantial body of directly relevant studies plausibly exists, and the answer will drive a major design decision. If access/resources prevent one, document that limitation and conduct a structured synthesis without claiming exhaustive coverage. Conceptual and policy-document history questions do not automatically require systematic reviews. Prefer structured narrative or best-evidence synthesis where measures or contexts differ. Do not vote-count studies or pool incompatible measures.

## 10. Traceability and effort triage
**Full chain required:** title-level synthesis; major causal/comparative claims driving design; national policy-status claims; load-bearing statistics; major recommendations. Trace Question/construct → Search → Selection → Appraisal → Finding → Interpretation → Counterevidence → Uncertainty → Value/design principle → Decision → Expected outcome → Failure mode.

**Lighter treatment permitted:** scene-setting facts that do not carry an argument. Cite source, date, and scope. Upgrade any background claim before it becomes load-bearing.

Map each link to repository artifacts: dated search log/export in `data/searches/`; source identity in `sources/source-register.md` and SRC-### records; findings/appraisal in `evidence/phase-NN/step-NN/`; interpretation and devil's-advocate pass in the step's `review-log.md`; and value premises, decisions, expected outcomes, and failure modes in `decisions/`.

## 11. Ethics gate
No original human-subject data collection begins without checking local law and requirements. If institutionally affiliated, seek ethics review; obtain school-head/managing-committee permission where applicable; for minors, obtain guardian informed consent and child assent; minimize identifiers and plan secure storage, anonymization, and retention. The current document-based phase does not require participant recruitment, but this gate must be revisited before any data collection.
