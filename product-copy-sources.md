# Products of Relevance — where the description copy comes from

Every line is existing Wolfram copy, used verbatim. Nothing is written for this section.
Re-verified against the live pages on 2026-09-02.

| Product | Line used | Source page | Where on that page |
|---|---|---|---|
| **Wolfram|One** | The definitive Wolfram Language and notebook experience | <https://www.wolfram.com/products/> | Product grid tagline, beside the Wolfram|One heading |
| **AI Products** | Add computational knowledge and Wolfram capabilities to make your AI smarter. | <https://www.wolfram.com/artificial-intelligence/> | Page meta description, first sentence |
| **Wolfram System Modeler** | Multidomain modeling and simulation of complex systems | <https://www.wolfram.com/products/> | Product grid tagline, beside the System Modeler heading |
| **Quezzio** | Flexible math & science classroom question generation and auto-grading for practice and assessment. | <https://www.wolfram.com/quezzio/> | Page meta description, first sentence |
| **Wolfram U** | Courses in computing, science, life and more | <https://www.wolfram.com/products/> | Product grid tagline, beside the Wolfram U heading |
| **Wolfram eTextbook Series** | Book collection covers computational topics, highly focused on real-world applications. | <https://www.wolfram-media.com/series/etextbooks/> | Page meta description, first sentence |

## How to check any of these yourself

For the three taken from the product grid, open <https://www.wolfram.com/products/> and find the
product; the line sits directly under its heading.

For the three taken from a meta description, open the source page, View Source, and search for
`<meta name="description"`. Our line is the first sentence of that tag. The full tag continues
past what we use, for example on the Quezzio page:

```html
<meta name="description" content="Flexible math &amp; science classroom question generation and
auto-grading for practice and assessment. Use alone or easily integrate with LMS platforms.">
```

## Two things worth knowing

- **The same line appears on every vertical page.** These describe the product, not the vertical,
  so Wolfram|One reads identically on AgTech, Civil Engineering and Math Education.
- **The register is deliberately mixed.** Three are short grid taglines with no full stop, three
  are full sentences. That is how the copy exists today. Rewriting any of them to match the others
  would make it new copy rather than existing copy, so they are left exactly as published.
