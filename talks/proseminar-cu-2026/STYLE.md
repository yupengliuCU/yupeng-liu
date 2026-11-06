# Style brief for Part 3 (Steam Early Access game project) of the CU ProSeminar deck, 6 Nov 2026

Send back ONE HTML file containing only `<section class="slide">…</section>` blocks for Part 3. The ProSeminar thread will restyle it and merge it into the deck. Content and numbers matter more than polish; layout will be redone to match.

## The deck
- Live deck: https://yupeng-liu.com/talks/proseminar-cu-2026/ (same engine and look as https://yupeng-liu.com/talks/eth-zurich-2026/; see its slide #d-demand for the hand-drawn sketch style).
- Each slide is a fixed 1920 x 1080 canvas, scaled to the window. Elements are absolutely positioned. Margins 128 px left and right; title at top 88 px; nothing below y 950 except a source line.
- Clicks: an element with class `frag` appears on the next click; elements sharing `data-fg="1"` appear together. Usually 1–2 clicks per slide, revealed top to bottom in reading order; a slide that visibly has three blocks may get three. Data/result slides 0–2.
- Speaker notes: `<aside class="notes">…</aside>` inside the slide (press n to show). Please write notes in plain spoken English.

## Look
- White background, no dark slides, no photo backgrounds, content first. One serif font (Newsreader). Seven text sizes only: 58 titles, 44 lede, 34 body, 28 secondary, 24 annotations, 20 sources.
- Colours: ink #10243F for almost everything, soft grey #4C5B70 for secondary text. Accent colours sparingly: blue #3F7FC4, green #2F8F6E (users/players and what they send back), red #D9432F (little per slide), gold highlighter at most once per slide.
- Titles are short nouns ("How Early Access works", "Modular vs. integrated games"), not sentences.
- Hand-drawn explainers (rough.js style, Kalam handwriting font) are welcome where a concept needs one: e.g. the Early Access loop (release unfinished → players buy and play → reviews, forum feature requests, bug reports → updates → 1.0), modular vs. integrated product architecture, a design structure matrix. No decorative figures, no cartoons for their own sake, no dot/arrow webs.
- Real material beats drawings: game covers / capsule images, a Steam store page with the Early Access banner, a forum "suggestions" thread, the paper's own figures and tables. For each image give the file (PNG/JPG, or a URL) and a one-line source.
- Footnotes only for sources, in small grey type at the bottom.

## Writing rules
- Slide text in English, short; prose over bullet dumps.
- Never use "lever", "levers" or "leverage".
- Don't invent claims or numbers: every number and result must come from the project's own files; mark anything preliminary as preliminary.
- Define a concept once, then only call back to it.
- Coauthor credit: "With Ashton Hawk".

## What Part 3 should cover (suggested)
1. Hook: a few recognizable Early Access games (covers).
2. How Steam Early Access works (sketch + store page screenshot).
3. Players as a source of ideas: feature requests, bug reports, reviews.
4. Product architecture: modular vs. integrated games (sketch).
5. Research question, data, measures.
6. Results, including the finding that feature requests slow down more in modular games (exact wording and estimates from the project).
7. Next steps / where feedback would help.
