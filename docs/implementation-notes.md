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

- Simplified the page toward the `ku-formal.github.io` style: compact header, text-first layout, bracket-style links, and minimal visual treatment.
- Kept the design restrained and readable because faculty-search readers need to scan credentials quickly.
- Replaced the large hero with a small floated portrait and a concise identity block.
- Prioritized selected publications from the existing SAL page, preserving paper, artifact, and venue links where available.
- Revised the research summary using the CV wording: automated software debugging with program analysis and program synthesis.
- Added education dates and a CV link from the supplied CV.
- Kept awards, talks, and other full-CV details inside the CV rather than duplicating them on the homepage.
- Kept the top navigation minimal and removed the duplicate name from the left side of the header.

## Files Created

- `index.html`: homepage content and semantic structure.
- `styles.css`: responsive visual design.
- `assets/profile.jpg`: supplied portrait for the homepage.
- `assets/CV/cv.tex`: supplied LaTeX CV source.
- `assets/CV/cv_dowon_song.pdf`: supplied CV PDF linked from the homepage.
- `docs/implementation-notes.md`: this documentation.

## Recommended Next Content

- Add dissertation title when finalized.
- Add professional service, invited talks, teaching experience, awards, and mentoring only when they become important enough to surface outside the CV.
- Add Google Scholar, DBLP, GitHub, ORCID, and CV links if available.
- Consider adding separate pages for publications and teaching once the content grows.
