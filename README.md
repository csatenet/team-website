# Team VOM: Lab 2 Website

**Live site:** https://csatenet.github.io/team-website/

## Team
| Name | Registration no. | GitHub username |
|------|------------------|-----------------|
| Samuel Odhiambo | COM/3614/25 | csatenet |
| Titus Kiptum | COM/8019/26 | tarzanjerry |

## Who drove each part
- Part 0, 2, 4: Samuel Odhiambo
- Part 1, 3: Titus Kiptum

## Personalisation
- Our colours:
  - Light theme: `--color-primary: #146c2e`, `--color-primary-dark: #0c471e` (paired with `--color-bg: #eef4f0` and `--color-surface: #ffffff`)
  - Dark theme: `--color-primary: #47dc76`, `--color-primary-dark: #7ef0a1` (paired with `--color-bg: #070b09` and `--color-surface: #0f1713`)
- Projects we added: **Tariq Online Shop** (`js`) and **Branching & Merge Workflow** (`git`), plus the `git` category and filter button.
- Extension challenge(s) completed: **E2 (Follow the system theme)** using `window.matchMedia('(prefers-color-scheme: dark)')` when no theme is saved in `localStorage`.

## Reflection
1. **Collaborating on a shared codebase:** Dividing the parts between Samuel and Titus worked best when we kept changes focused on specific files and communicated before editing shared stylesheets or scripts.
2. **Working with Git and branches:** Using clear commits and pulling before starting a session helped prevent avoidable conflicts and kept our repository history readable.
3. **Styling for a distinct vibe without sacrificing readability:** Leaning into a dark, eerie *Pluto*-inspired green-and-shadow aesthetic felt memorable, while checking contrast ensured headings, links, and buttons stayed legible.
4. **JavaScript state and DOM rendering:** Dynamically rendering project cards from data and filtering by category (including our new `git` filter) made updating the page straightforward without duplicating HTML cards.
5. **Accessibility and keyboard navigation:** Checking focus visibility, semantic landmarks, labels, and contrast highlighted how small HTML mistakes—like broken skip links or mismatched page states—affect real users.
6. **Testing across screen sizes and deployment:** Checking layout behaviour at 375 px, running validation and Lighthouse checks, and verifying the live GitHub Pages URL caught issues that are easy to miss on a single desktop view.