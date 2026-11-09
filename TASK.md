# TASK.md

## Audience
A prospective first-year student, probably on a phone, who knows an interest or a job they want but not the official name of the major.

## Page chosen
Alvernia undergraduate programs page: https://www.alvernia.edu/undergraduate

## Problem
The page lists about 50 programs in one alphabetical list with no search or filters. Four-year majors, accelerated tracks (3+3, 3+2, 5-year) and an online completion program are mixed together. Some names do not say what the field is (for example "Human Problems and Sustainable Solutions").

## Feature
A "Find a major" section: a search box that also matches interest words (for example "coding" or "sports"), filter chips for area of study and program type, result cards that link to the official program page, and a helpful empty state.

## Acceptance criteria
1. Typing an interest word (such as "coding", "nursing" or "sports") narrows the list on every keystroke and the result count is announced to screen readers.
2. Area and program-type filters can be combined with search, and every result shows its type as text and links to the official program page.
3. A search with no matches shows a clear message with three next steps: clear filters, the Exploratory Program, and a link to ask admissions.

## Also checked
- Phone layout at about 375 px wide: no sideways scrolling, tap targets at least 44 px.
- Keyboard: search, chips, reset and result links reachable in order with a visible focus ring; Esc clears the search.
- Failure state: if the list cannot render, the page says so and links to the official list.

## Out of scope
Live chatbot, paid API, new map or 3D features, minors and pre-professional programs, editing the real Alvernia site.

## Data note
Program names and links were copied from the live page on Nov 9, 2026. The area groups and search words were written by the AI agent and need human review.

## Peer visitor task
"Find a program that combines sports and business, then open its official page."
