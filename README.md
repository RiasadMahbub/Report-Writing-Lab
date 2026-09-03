# Report Writing Lab

A personal reference repo for learning the writing style, structure, and analytical
method used in institutional sustainability / economic / climate-finance reports
(World Bank, IMF, WEF, UNEP, Yale EPI, and allied think tanks), built from a close
reading of the reports listed in [`sources/links.md`](sources/links.md).

Goal: internalize the house style well enough to write credible practice reports —
useful prep for analyst roles at these kinds of institutions.

## Structure

```
report-writing-lab/
├── sources/
│   └── links.md              # every source report, tagged by org/genre
├── style-guides/
│   ├── world-bank.md         # World Bank Sustainability Review style breakdown
│   ├── imf.md                 # IMF corporate + research report style breakdown
│   ├── wef.md                 # WEF Global Risks Report style breakdown
│   └── comparison.md          # cross-institution comparison table
├── templates/
│   ├── corporate-esg-section-template.md
│   ├── research-note-template.md
│   └── policy-brief-template.md
└── practice/
    └── README.md              # where to drop your own practice drafts
```

## How to use this

1. Read `style-guides/comparison.md` first — it's the map of which genre you're
   writing in and which template fits.
2. Pick the matching template from `templates/`.
3. Write a short practice piece and drop it in `practice/`.
4. Compare it sentence-by-sentence against the relevant style guide's "sentence
   patterns" section.

## Pushing this to your own GitHub

This folder is already a git repo with one commit. To publish it:

```bash
# create an empty repo on github.com first (no README/license), then:
git remote add origin https://github.com/<your-username>/report-writing-lab.git
git branch -M main
git push -u origin main
```
