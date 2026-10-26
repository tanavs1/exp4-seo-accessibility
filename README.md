# Experiment 4 - SEO and Accessibility Optimization

For Web Development Lab (Week 4). `before.html` is the original page and
`index.html` is the optimized version of the same page.

## Changes made

| Problem in before.html | Fix in index.html |
|---|---|
| No `lang` attribute, no meta tags, title was just "Page" | Added `lang="en"`, a proper title, meta description, keywords, author, robots, canonical link and Open Graph tags |
| Page heading was a `div` and headings were in the wrong order (h4 then h1) | One `h1`, then `h2` for sections and `h3` for sub-topics |
| Everything was a `div` | Used semantic tags: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer` |
| Image had no alt text | Added a descriptive `alt`, plus `width` and `height` |
| Menu was made of `span` tags and did nothing | Real links (`a` tags) inside `nav` with an `aria-label` |
| Input had no label and "Subscribe" was a `div` | Added a `label` linked with `for`/`id`, and a real `button` |
| No way to skip the menu with a keyboard | Added a skip link |
| No focus outline, low contrast text | Added `:focus-visible` outlines and darker text colours |
| No table structure | Used `caption`, `thead` and `th scope` |

## Live site
https://tanavs1.github.io/exp4-seo-accessibility/
