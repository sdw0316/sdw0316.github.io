# Implementation Notes

## Goal

This homepage was built as a faculty-application-oriented personal academic site for Dowon Song. The design emphasizes quick review by hiring committees: identity, position, research area, selected publications, background, and contact information appear in a predictable order.

## References Reviewed

- Current lab member page: https://prl.korea.ac.kr/members/dowon-song/
- Wonseok Oh: https://marinelay.github.io/
- Minseok Jeon: https://dgistpl.github.io/members/minseok.jeon/
- Formal Software Verification @ KU: https://ku-formal.github.io/
- Sooyoung Cha: https://sites.google.com/view/sooyoungcha

## Reflected Decisions

- Used a concise academic CV structure inspired by the reference pages: profile summary, research interests, publications, experience and education, activities, and contact.
- Kept the visual design restrained and readable rather than marketing-heavy, because faculty-search readers need to scan credentials quickly.
- Placed a portrait and a research-position summary in the first viewport so the site immediately identifies the person and field.
- Prioritized selected publications from the existing SAL page, preserving paper, artifact, and venue links where available.
- Wrote the research summary from the visible publication record: automated program repair, semantic patch validation, program analysis, feedback generation, and logical-error detection.
- Added a placeholder Activities section that can later be expanded with program committees, artifact evaluation committees, talks, teaching, awards, grants, and mentoring.

## Files Created

- `index.html`: homepage content and semantic structure.
- `styles.css`: responsive visual design.
- `assets/dowon-song.webp`: portrait copied from the existing lab member page for local use.
- `docs/implementation-notes.md`: this documentation.

## Recommended Next Content

- Add a current CV PDF and link it from the hero area.
- Add complete education dates and dissertation title.
- Add professional service, invited talks, teaching experience, awards, and mentoring.
- Add Google Scholar, DBLP, GitHub, ORCID, and CV links if available.
- Consider adding separate pages for publications and teaching once the content grows.
