# Content Audit — Session 9 Portfolio (upgraded version)

| Content | True? | Evidence / What was removed |
|---|---|---|
| Name: Mubashshira Ali Khan | Yes | Your real name, supplied by you |
| Title: Data & AI Practitioner | Yes | Supplied by you |
| Education: B.Tech in CSE (AI & Data Science), undergraduate | Yes | Supplied by you. No institution, year or grades were added |
| Hero / About text | Yes | Written only from the details you supplied; no achievements, experience or certifications added |
| Prompt Engineering | Yes | Skill you have learned/practiced. Description is generic; no tools named |
| Artificial Intelligence & Machine Learning | Yes | Skill you have learned/practiced |
| Exploratory Data Analysis (EDA) | Yes | Skill you have learned/practiced |
| Machine Learning Model Development | Yes | Skill you have learned/practiced |
| Data Visualization | Yes | Skill you have learned/practiced |
| Skill ratings / percentages | N/A | None used |
| Student Attrition Prediction | Yes | Your actual project. Description kept general, derived from the title only |
| NoBrokerage.com Chatbot | Yes | Your actual project. Description kept general, derived from the title only |
| Project technologies | Placeholder | Marked `[Add the technologies you used]`; nothing assumed |
| Deployment claims | N/A | No project is described as deployed |
| Email / Phone | Placeholder | Email is a marked placeholder; no phone number is shown |
| GitHub profile: https://github.com/mubashshira1530-rgb | Yes | URL supplied by you. Page fetched: profile exists with 5 public repositories. Used in the nav icon link and the "Explore My GitHub" button |
| LinkedIn / other links | Placeholder | Marked placeholders; no URLs or accounts invented |
| Project repository links | Placeholder | Not provided, so none shown as links. Your profile lists repositories (Session-10, Session-10a, session-12, fitnessapp, Hardik-Portfolio) but none was assumed to match either project. "View Project" buttons stay inactive until you give exact URLs |
| Resume | Placeholder | "View Resume" / "Download Resume" have no `href` until a resume file exists |

## Removed in this upgrade

The previous version's project descriptions went beyond what you had told me
(e.g. "supervised learning", "data cleaning", "evaluation of the trade-off between
catching at-risk students and false alarms", "intent handling", "guides visitors to
relevant listings"). Those details were removed. The current text only restates what
the project titles support.

## Validation — what was actually run

| Check | Result |
|---|---|
| Exactly one `<h1>`, containing the full name | Pass (HTML parser) |
| Inline `style=` attributes | 0 found (HTML parser) |
| `<style>` tags | 0 found |
| `<script>` tags and `on*` event attributes | 0 found |
| CSS linked via `<link rel="stylesheet" href="style.css">` | Pass |
| Duplicate `id` values | None |
| In-page links (`#home`, `#about`, `#skills`, `#projects`, `#contact`, `#main`) all resolve to a real `id` | Pass |
| Failed network requests / console errors on load (headless Chromium) | None |
| Horizontal overflow at 375px width (headless Chromium) | None (scroll width = 375) |
| Horizontal overflow at 1280px width (headless Chromium) | None |
| Visual review of screenshots at 375px and 1280px | Done |
| GitHub links: only one URL used (your profile); `target="_blank"` and `rel="noopener noreferrer"` on both | Pass (HTML parser) |
| GitHub button click opens a new tab (headless Chromium, desktop) | Pass. Destination could not load: the test environment is offline |
| Adding an `href` to a project button activates it and hides its note (temporary copy) | Pass |
| Nav stays on one row with the GitHub icon at 375px, 800px and 1280px | Pass |
| Colours used in CSS | Light blue `#C6E0F4` / paler `#EAF4FB`; pink `#F28DB2` / paler `#FDEAF1` / deeper `#A92C60` for small text; deep slate `#1E2B45` for text; white for card surfaces. Navy and teal fully removed |
| Text contrast (calculated WCAG ratios for every text/background pair used) | Pass: every text pair is at least 4.5:1; the lowest is deep pink on light blue at 4.8:1 (hero label) |

## Validation — NOT run

- **W3C Nu HTML Checker:** not run. The validator is not available in this environment and
  there is no network access. The earlier version of this file claimed "0 errors";
  that claim was not backed by a test and is withdrawn. Run the page through
  https://validator.w3.org/nu/ before relying on it.
- **CSS validator (W3C Jigsaw):** not run.
- **Real devices / other browsers (Safari, Firefox):** not tested; only headless Chromium.
- **GitHub link loading from the live site:** the profile page was confirmed to exist by fetching it, but the clicked link could not be loaded inside the offline test environment.
- **Third-party contrast checker tool:** not run; ratios were calculated by script from the hex values, not measured on rendered pixels.

## Placeholders needing your real information

1. Project 01 technologies, and its exact repository URL (`View Project`)
2. Project 02 technologies, and its exact repository URL (`View Project`)
3. Resume link (`View Resume`, `Download Resume`)
4. Professional email
5. LinkedIn profile
6. Other professional link (optional; delete the list item if unused)

The GitHub profile is no longer a placeholder.
