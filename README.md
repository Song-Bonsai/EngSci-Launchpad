# EngSci First-Year Launchpad

A homepage for first-year Engineering Science students at U of T, plus **Unit Map**, a weekly course breakdown mapped onto your own timetable.

- `index.html` is the launchpad (the page visitors land on)
- `unit-map.html` is Unit Map, linked from the launchpad's "this week" strip

Both are plain, self-contained HTML files. No build step.

## Updating each term

**Launchpad (`index.html`):** open the file and find the block marked `EDIT THESE EACH TERM` near the top of the script.

- `COURSES`: Quercus links (course IDs change every offering) and courses.skule.ca links
- `TERMS`: class start/end, study break and exam dates from the Engineering Academic Calendar

**Unit Map (`unit-map.html`):** update `TERM`, `PRESETS` and `NO_WEEKLY_SYLLABUS` in the script.

## Hosting

Published with GitHub Pages from the repository root. Every commit to the publishing branch redeploys the site within a minute or two.
