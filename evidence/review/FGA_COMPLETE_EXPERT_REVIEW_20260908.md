# Korean FGA cumulative edition — expert review record

## Scope and status

This record covers the complete Korean FGA component sequence
`149,e149,182,e182,190,e190,195,e195,212,e212,221,e221,232,e232,236,e236,com`.
All components have been translated from the maintained French authority and
integrated in canonical order. The paired English edition was used only to
resolve semantic ambiguities. This record is a human-readable map to the
machine-readable occurrence ledgers; it is not a second content-QA pass and it
does not assert that a human expert has approved the edition.

## Authority and register

The maintained French text governs statements, hypotheses, formulae,
quantifier scope, source-page markers, notes, citations, and historical
errata relations. Professional Korean algebraic-geometry writing governs
terminology, idiom, syntax, and adult register. Existing Korean EGA and Stacks
passages were used as same-language comparanda only when their own source and
canon evidence was available; agreement among project translations was never
treated as independent proof of conventional usage.

## High-value choices and boundaries

- Historical `préschéma` remains `준스킴`; it is not silently modernized to
  `스킴`. Geometric `de type fini` is `유한형`, kept distinct from finite
  generation of modules or groups.
- The descent family is rendered compositionally with `하강`: `하강 기법`,
  `하강 데이터`, and `F-하강 사상`. A production-discovered inconsistency in
  Exposé 195 was normalized once to this same-work family. Quoted external
  Korean evidence using `강하` was preserved as contrary evidence rather than
  rewritten.
- `représentable`, `pro-représentable`, and `strictement pro-représentable`
  remain distinct as `표현 가능`, `프로표현 가능`, and `엄밀하게 프로표현
  가능`. Categorical monomorphisms, epimorphisms, set-theoretic injections,
  and surjections are not collapsed.
- Quotient, Hilbert, and Picard objects retain their mathematical types:
  `몫 준스킴`, `힐베르트 스킴`, `피카르 군`, `피카르 함자`, `피카르
  준스킴`, and `피카르 스킴` are used only where the source asserts the
  corresponding object. In particular, `Pic'` and the sheafified relative
  `Pic` construction are not merged.
- In Exposé 236 the historical adjective `séparable` is resolved by the
  source's own parenthesis as flatness with separable fibres (`분리 가능`),
  not separatedness (`분리`). The group-translation argument resolves the
  historical false friend `simple` as smoothness, not group-theoretic
  simplicity.
- Errata components preserve both the printed and corrected readings. They do
  not silently substitute a corrected text and erase the historical relation.

## Explicit uncertainties

The occurrence ledgers mark weakly attested surface forms instead of inventing
authority. The principal remaining lexical uncertainties are the conventional
surface of historical strict pro-objects and `유계인 족` for Grothendieck's
bounded families. Their mathematical definitions, arrow directions, and
applicability are source-explicit, so the current wording is a reversible,
evidence-based provisional decision rather than a release hold.

## Evidence map

The source/target occurrences, exact consulted passages, stable identities,
rationales, rejected alternatives, and confidence reasons are in
`controls/FGA*_CHOICES.jsonl` and `fga/149.choices.jsonl`. Integration receipts
are `controls/FGA182_E182_SINGLE_COMPONENT_INTEGRATION_20260908.json`,
`controls/FGA190_E190_195_E195_SINGLE_COMPONENT_INTEGRATION_20260908.json`,
`controls/FGA212_E212_221_E221_SINGLE_COMPONENT_INTEGRATION_20260908.json`,
`controls/FGA232_E232_SINGLE_COMPONENT_INTEGRATION_20260908.json`, and
`controls/FGA236_E236_COM_SINGLE_COMPONENT_INTEGRATION_20260908.json`.

The cumulative reader will receive one corpus-level build and one whole-reader
check. No per-section content-QA loop or repeated content-QA loop is permitted.
