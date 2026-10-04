# Project-owner decisions

Record explicit project-level decisions that change scope, source authority, terminology, release contracts, or workflow.

Do not use this file for every locus-level editorial decision; those belong in the diplomatic decision ledgers.

## Active decisions

<a id="terminology-clarification-2026-10-04"></a>

### 2026-10-04 — Bounded issue #2 terminology clarification (P1)

**Authorization:** after reviewing [issue #2](https://github.com/Lotus-King-Translation/tibetan-text-project-template/issues/2) and the proposed bounded patch, the owner instructed: “Do the changes/updates now in the template repo.” The approval concerns the specific five-row/three-amendment proposal, not every alternative interpretation listed in the issue.

**Scope and version:** template only; translation standard **2.0.1** and glossary clarification revision **2026-10-04 (P1)**. Retain the standard's existing filename. Baseline template commit: `f6431c25c7c9fa852c404b8cd3e0e3cdeae1178f`. All 222 Tibetan–English assignments, row order, eight columns and unrelated supplementary cells remain unchanged. No new headwords, files, tools, schemas or review stages are introduced.

**Approved glossary clarifications:** the operative conditions and exclusions are recorded in the five existing rows, with P1 provenance:

| Existing assignment, unchanged | Approved clarification | Issue group |
| --- | --- | --- |
| རྒྱུད་ → Continuum | Literary **tantra** only for unambiguous tantric scripture/text-genre uses; retain other senses and whole-expression precedence | G11 |
| སྒྲ་ → Word | Auditory **sound** where the sense is supported; retain linguistic whole expressions and review ambiguous extensions | G14 |
| འབྲས་བུ་ → Result | Botanical **fruit** and explicitly sustained tree/fruit metaphors, not blanket stylistic alternatives | G17 |
| གཞི་ → The Ground | Technical **Ground**, with ordinary article grammar; no adjudication of disputed support/other senses | G13 |
| གཞི་སྣང་ → Ground-appearance | Consistent technical capital G and existing hyphenation | G13 |

**Guidance:** Part I §3.3 now addresses overlapping source modifiers and established English components without automatic duplication or loss; §6 requires reuse of adopted shared approved usages rather than competing chapter/book defaults; §9 defers to approved glossary presentation rules. Part II extends R04/R11/R18 and adds R31–R34, retaining all existing IDs and the other expected distinctions. Normal grammatical variation still needs no new lexical approval.

**Not approved or performed:** no general logical-property, physical-movement, separating/secret-preliminary or nominal-apprehension exceptions (G12/G15/G16/G18); no final adjudication of the individual G19 vajra passages. Other pending proposals remain pending. G01–G10 remain translation-remediation tasks, not reasons to add synonyms. No sibling repository, Tibetan source, English translation or release tag is changed, and issue #2 remains open.

**Adoption:** consuming projects must explicitly adopt the new glossary/standard versions and recheck affected occurrences. Do not overwrite inputs bound to historical releases. This template update is not a claim that existing translations have been corrected or brought into compliance.

**Validation:** Structural checks passed: all 222 base assignments, their order and the eight columns are unchanged; exactly five glossary records changed, with the other 217 raw records unchanged. All 29 other tracked files are unchanged. The fixture table has 34 unique IDs, with 27 original fixture rows unchanged. Seven in-memory corruption controls covering assignment/headword changes, row order/count, schema, unrelated supplementary edits and duplicate/replaced rows were rejected. `git diff --check` and the existing paired-template validator passed (zero placeholder pairs). The seven affected fixture specifications were manually reviewed; no translation/QC model benchmark or independent philological certification was performed.

**Content identities:** glossary SHA-256 `07e1b3a567aa6abb72fac931b23830deba68de14477a9c3b147296d960995ce4`; standard SHA-256 `710abf09ac7b98f6cb092dec11493787425280cc52031b2c1b41d8fe477e89c2`.

## Decision record template

- Date:
- Decision:
- Scope:
- Supersedes:
- Evidence/context:
- Affected files/sections:
