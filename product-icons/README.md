# Product icons

The six marks used in the Products of Relevance section, in the colour they render on the page
(`#D1C4FF`, the page's `--purple-light-accessible` token).

| File | viewBox | Size |
|---|---|---|
| `ai-products.svg` | `-4.57 -3.46 68.34 68.34` | 3,309 B |
| `quezzio.svg` | `-2.27 -9.99 59.72 59.72` | 843 B |
| `wolfram-etextbook-series.svg` | `-12.23 -6.72 85.01 85.01` | 3,680 B |
| `wolfram-one.svg` | `-0.49 -0.43 35.85 35.85` | 588 B |
| `wolfram-system-modeler.svg` | `-1.78 -1.01 38.05 38.05` | 9,179 B |
| `wolfram-u.svg` | `-4.04 -4.04 44.06 44.06` | 2,882 B |

Every viewBox is square and frames its glyph with equal padding, so all six render at the same
apparent size when given the same height (40px on the cards, 36px on the rows). Replacing a mark
means re-running the sizing pass or it will not match the others.

Sources: Wolfram|One, System Modeler and Wolfram U come from wolfram.com's own navigation icon
set; Quezzio from `wolfram.com/quezzio/img/quezzio-icon.svg`; AI Products and the eTextbook
Series mark were supplied by design.
