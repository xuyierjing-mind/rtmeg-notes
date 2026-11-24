# Real-time MEG notes (MEGIN + FieldTrip, MATLAB first)

Beginner-oriented notes on real-time MEG data processing. The whole site is one self-contained file, `index.html`; it loads no external scripts, fonts or images.

## View locally
Open `index.html` in a browser. Pages are switched with the URL hash (`#p0` to `#p7`).

## Publish with GitHub Pages
1. Repository → Settings → Pages.
2. Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site appears at `https://<user>.github.io/<repo>/`. Sub-pages: add `#p3` etc.

## Contribute
- Edit `index.html` on a branch; open a pull request; one maintainer merges.
- Each page is a `<section id="pN">`. Keep sources in section `p7` and cite them as `[S#]`.
- Mark anything not independently checked as "unverified".
- Lab measurements (page 03): record date, system, software version, chunk size, cHPI on/off.
- Add one line to `CHANGELOG.md` per change.

## Before making the repository public
The site contains lab-specific details (a hostname, a folder path, the operator manual's author and date). Remove or generalise them if the repo is public.
