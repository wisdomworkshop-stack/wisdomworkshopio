# wisdomworkshop.io

The Wisdom Workshop website. Plain HTML, no build step. Netlify deploys the `main` branch automatically; every pull request gets its own preview link.

## Pages

| File | Address | What it is |
| --- | --- | --- |
| `index.html` | / | Homepage: the perMA, the practice, "Other ways in," voices, about |
| `perma.html` | /perma | The Personal Master of Arts |
| `perma-apply.html` | /perma-apply | perMA application |
| `perma-tracker.html` | /perma-tracker | perMA requirements and tracker |
| `good-life-facilitation.html` | /good-life-facilitation | Good Life Facilitation course page (Nov 10 – Dec 18, 2026) |
| `good-life-facilitation-syllabus.html` | /good-life-facilitation-syllabus | Good Life Facilitation syllabus |
| `world-philosophy.html` | /world-philosophy | World Philosophy Workshop (Fall 2026, complete) |
| `world-philosophy-apply.html` | /world-philosophy-apply | World Philosophy application |
| `writing-a-good-life.html` | /writing-a-good-life | Writing a Good Life |
| `privacy-policy.html` | /privacy-policy | Privacy policy |
| `welcome-gifts/` | /welcome-gifts/… | Welcome pages for each course |

Netlify serves `name.html` at `/name`, so link to pages without the `.html`.

## Naming a new course

One file per course, named for the course: `good-life-arts.html`, with `good-life-arts-syllabus.html` beside it if the syllabus is its own page. When a course ends, leave its page up (old links keep working) and stop featuring it on the homepage.

## Each new season: homepage checklist

Course dates appear in several places on `index.html`. Change all of them together:

1. `<title>` and `<meta name="description">` at the top
2. The nav link "Next Workshop"
3. The hero: badge, the last sentence of the lede, the "Next doorway opens" line, the second button, and the note under it
4. "The Year" note ("Prefer to start smaller?…")
5. "Other ways in": move the featured card (`also-card feature`) to the new course and update the waitlist cards
6. The closing section ("The next doorway opens…") and its syllabus button
7. The footer links

## Making changes

1. Make a branch, or let GitHub make one when you edit a file on github.com and choose "Create a new branch."
2. Open a pull request. Netlify posts a preview link on it within a minute or two.
3. Click through the preview. When it looks right, press **Merge**. The live site updates shortly after.
