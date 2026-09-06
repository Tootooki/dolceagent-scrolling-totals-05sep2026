# DOLCE AGENT — Scrolling Totals

Based on `dolceagent-centered-uppercase-dates-05sep2026`.

The PPC totals row now scrolls vertically with the data. The column-name row remains frozen at the top. The blank first totals cell retains only horizontal freezing so the first-column boundary remains intact while scrolling sideways.

Only totals positioning CSS and its stylesheet version changed. Totals calculations, the shared menu slider, centered uppercase dates, data-row resize guide and other existing features are preserved.

Verification: mobile browser checks showed 219px of table scrolling moved every totals cell from y=62 to y=-157 while the column-name row stayed at y=30. Returning to the top restored the totals. Horizontal scrolling by 533px kept the first heading and first totals cell at x=0. No browser errors were reported.

Publish with `npm run publish`.
