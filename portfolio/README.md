# Portfolio redirect

This directory preserves the historical `/delta-pi-hub-privacy/portfolio/`
address while the full Javonn Liner apps and games portfolio lives at
`https://javonn13.github.io/`.

`index.html` provides a clear fallback link and redirects visitors when
JavaScript is available. The redirect carries the existing URL fragment to the
new address, so links such as `#projects` and `#contact` continue to target the
same section when it exists there. Its canonical URL is the new portfolio root.

The existing assets and stylesheet remain in this directory intentionally.
