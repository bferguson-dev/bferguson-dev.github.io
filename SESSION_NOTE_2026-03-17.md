# Session Note - 2026-03-17

## Current repo state

- Repo: `bferguson-dev.github.io`
- Purpose: dedicated GitHub Pages portfolio site at account root
- Deployment: GitHub Pages via GitHub Actions
- Main workflow file: `.github/workflows/deploy-pages.yml`
- Site URL: `https://bferguson-dev.github.io/`

## Current homepage status

- Live homepage is still the polished-corporate version in `index.html`
- Name has been updated to `Byron Ferguson`
- Homepage copy was tightened to be more recruiter-facing and less placeholder-like
- Featured project remains `FailWarden Orchestrator`

## Project pages currently in repo

- `projects/failwarden-orchestrator/`
- `projects/ymc/`
- `projects/loadout/`
- `projects/readycheck/`
- `projects/my-lab-setup/`

## Important content constraints already reflected

- FailWarden copy is intentionally honest:
  - public solo-maintainer repo
  - current tagged release `v0.2.0`
  - V1 implemented
  - V1.5 implemented
  - planned V2 scope
  - strong unit and controlled local integration coverage
  - not yet validated against real production infrastructure or live notifier endpoints

## Style preview pages currently available

Existing earlier previews:

- `style-previews/minimal.html`
- `style-previews/bold.html`
- `style-previews/executive-brief.html`
- `style-previews/technical-dossier.html`
- `style-previews/case-study-editorial.html`
- `style-previews/operator-console.html`
- `style-previews/consulting-profile.html`
- `style-previews/fun-lab-notebook.html`

Newer previews based on user feedback:

- `style-previews/clear-signal.html`
- `style-previews/modern-console-lite.html`
- `style-previews/guided-overview.html`

## User feedback captured this session

- Likes the text style of `operator-console`
- Does **not** want the industrial / 1970s-feeling color schemes
- Likes the top nav link presentation on the current homepage
- Does **not** want the site to feel like a technical paper
- Does **not** want it to read like a blog
- Wants extremely fast first-impression clarity
- Wants it to be executive / recruiter ready
- Still wants enough engineering-manager signal without forcing deep navigation
- Wants more personality in the design
- Asked to keep current, executive, case study, console, and consulting pages for review

## Best candidates to revisit first

Based on the most recent discussion, the strongest next candidates are:

- `style-previews/clear-signal.html`
- `style-previews/modern-console-lite.html`
- `style-previews/guided-overview.html`

Most likely next step:

1. User picks a preferred direction or top 2.
2. Merge the strongest qualities into `index.html`.
3. Keep the final homepage highly scannable:
   - immediate role/value statement
   - featured proof project
   - visible supporting projects
   - optional depth on the same page or one click away
4. Later add public contact links when user is ready.

## Recent commits to know about

- `23bcf07` Initial portfolio site
- `3d268ce` Remove duplicate Pages workflow
- `b48e9da` Refine homepage and add style previews
- `0cdfaee` Add additional homepage style previews
- `368ca41` Add fun style preview
- `ef0e305` Add faster-reading homepage preview variants

## Note for next session

Do not start by generating more random styles.
Start by asking the user which of these is closest:

- `clear-signal`
- `modern-console-lite`
- `guided-overview`

Then converge toward one final homepage instead of continuing to branch.
