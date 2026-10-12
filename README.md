
 Tendekayi Matizanadzo — Personal Profile

A personal mini-portfolio page built with semantic HTML5 and a
validated contact form.

## Prompt Log
See [PROMPT_LOG.md](PROMPT_LOG.md)

## Accessibility Review
<!-- My peer was not able to see the picture and also the text due to the color contrasts and i changed the contrasts to match my background and fixed the image. -->
**Issue found:**
**Fix applied:**

# my-repositoryy
html website creation


## Responsive Notes

**Breakpoints tested:** 375px (mobile), 768px (tablet) and 1280px (desktop) using
the Edge DevTools device toolbar. No horizontal scrolling, overlapping text, or
console errors at any of the three widths.

**Flexbox vs Grid:** Flexbox is used for the navigation links and the skills pills,
because they are single rows of items that need to wrap. Grid is used for the page
layout in `main`, because it needs rows and columns (About beside Skills on desktop
using `2fr 1fr`).

**Tailwind vs custom CSS:** Tailwind utility classes style the header/nav and the
contact form, including the `sm:` responsive variants. Everything else (base
typography, colours, section cards, skills, footer and the media queries) is in
`profile.css`. No element is styled by both.

**Mobile-first:** the base CSS targets small screens, and `min-width` media queries
at 768px and 1024px add the tablet and desktop layouts.

