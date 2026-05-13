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
- Placed a compact portrait and a research-position summary in the first viewport so the site immediately identifies the person and field without making the photo visually dominant.
- Prioritized selected publications from the existing SAL page, preserving paper, artifact, and venue links where available.
- Revised the research summary using the CV wording: automated software debugging with program analysis and program synthesis.
- Added education dates, awards, selected talks, and a CV link from the supplied CV.
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
- Add professional service, invited talks, teaching experience, awards, and mentoring.
- Add Google Scholar, DBLP, GitHub, ORCID, and CV links if available.
- Consider adding separate pages for publications and teaching once the content grows.
