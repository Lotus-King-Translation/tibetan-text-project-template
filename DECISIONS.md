# Project-owner decisions

Record explicit project-level decisions that change scope, source authority, terminology, release contracts, or workflow.

Do not use this file for every locus-level editorial decision; those belong in the diplomatic decision ledgers.

## Active decisions

<a id="terminology-expansion-2026-10-05"></a>

### 2026-10-05 — Approved issue #1 additions and matter/karmic-being clarification (P2)

**Authorization:** the owner accepted the proposed U15–U44 treatments in chat and instructed implementation in the template, except that U35 should not use the proposed insentient-matter label. The owner explicitly confirmed **karmic being** for སེམས་ཅན and suggested **matter** for བེམ་པོ/བེམས་པོ, subject to comprehension. P2 implements matter with a source-sensitive scope note, rather than reintroducing sentience vocabulary. Earlier firm decisions in [the owner's issue comment](https://github.com/Lotus-King-Translation/tibetan-text-project-template/issues/1#issuecomment-5978887526) remain authoritative. Approval concerns these proposed defaults and their stated conditions, not unconditional application to disputed clauses.

**Finite scope:** template only; baseline `cd9d1c26ee70dc7d486b50c2d9df1244613215f5`. Append **61 records**, including separate attested forms, for **283 total glossary rows**. This covers all **30 groups U15–U44**, six earlier groups with specifically settled implementation (U01/U03/U04/U09/U11/U14), and the newly reconfirmed karmic-being convention. The original **222 Tibetan–English assignments remain unchanged and in order**. Correct only status/provenance fields in two existing rows that still called standalone ཐུགས absent. Update the existing combined standard to **2.0.2**, retaining its filename; update the decision/status/handoff records and issue #1. No translation or source publication is part of this patch.

**Approved defaults and controls:** exact forms, grammar, triggers, exclusions, related entries and pinned source evidence are in the existing CSV, not a competing synonym list. U15–U44 follow the accepted proposals. The linked cluster is **essence / core / pure extract / quintessence**; core never becomes essence, and no general core-to-quintessence exception is activated. Existing whole-expression assignments, including Mahamudra, retain precedence. Earlier firm entries added here are the full/short **Blessed One**, the proper name **Vajradhara**, **sacred pledge**, **transmission**, **key point**, and **core**.

**U35:** use **matter** as the mass noun and **material thing(s)** where the source requires count grammar. The relevant knowing/non-knowing distinction must remain intelligible, with a source-linked explanatory note where the concise label obscures it. Matter does not mean immobile, dead, lifeless or non-karmic being, and does not imply that karmic beings lack material bodies. It does not replace every occurrence of body, entity or substance. Selected checks: DTG-000111/000869, SMB-000047/000050 and MTP-000540/000550. The default is implemented; disputed comprehension or clause interpretation remains locally reviewable.

**U36/U40:** citta is an approved **retention policy**, not certification of a heart/anatomical identity. Awakened mind is approved for standalone ཐུགས in the cognitive/honorific scope. Heart/location passages and the unresolved Pearls clauses remain open to construction-level review. Lexical approval alone must not remove their uncertainty markers.

**Not silently approved:** U02's specific Joy-Maker/Delight-Maker/Maker-of-Joy choice; U05's affliction/mental-state defaults; U06's bsam gtan label; U07's every-occurrence itself treatment; U08's thabs rule; U10's superficial/superfactual pair; U12's phrase/word rule; U13's luster/lustre decision. The English equivalent for Tathāgata and the distinct rdo rje dzin title also still need explicit selection. Neither this patch nor a settled proper-name entry turns those open questions into approved defaults. The owner-approved U15–U44 label choices do not decide every disputed historical passage.

**Guidance and examples:** recognize scoped Approved P2 entries alongside the preserved original assignments; preserve complete karmic-being wording and avoid an invented inverse relation to matter; distinguish English honorifics from retained proper names and compositional epithets. Remove obsolete standalone-thugs absence claims in Parts I/II and R24. Add **R35–R57**, yielding **57 fixture specifications**, covering both conforming treatments and prohibited overextensions. These extend the existing section only.

**Adoption and remaining work:** template encoding is complete (**61/61 rows; 30/30 approved new groups**). Eight earlier groups still need specific choices, with the partial honorific/title questions noted above. All four books still require explicit glossary/standard adoption and source-sensitive English/note revisions. Do not overwrite historical release inputs, rewrite Tibetan, or treat issue #1 as closed. Issue #2's existing translation departures are not corrected by adding entries here.

**Validation:** Structural/source-reference checks passed: all 222 original assignments and their order preserved; the eight-column schema unchanged; 220 original raw records untouched, with only status/provenance fields changed in the two obsolete standalone-thugs documentation records. All 61 additions have explicit approval, scoped usage and verified pinned Tibetan occurrence references; no new duplicate headwords. 14 in-memory corruption controls were rejected. All 33 unchanged original fixtures and P1 expected results are preserved; R24 is updated and R35–R57 added. The existing paired-template validator passed with zero placeholder pairs, and git diff --check passed. New fixture specifications and selected matter/citta/related-term examples were self-reviewed, not independently certified; no translation-model benchmark, full book retranslation, scan proofreading or exhaustive new semantic audit was performed. 27 unrelated tracked files are unchanged; no new tracked file, tool, schema or review stage is introduced.

**Content identities:** glossary SHA-256 `f767cd8af409bc16a6ed41bb086d23d1f204cb6db76c48189c168a9a95401da7`; standard SHA-256 `c1b8e91dcfc858fa3b87bb0adba63f98b28ff273f350e34cf9d45e82951cfbbb`. This is a template maintenance commit, not a new fixed Tibetan or English release; no tag is created or moved.

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
