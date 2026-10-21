<!-- LOVABLE:BEGIN -->

> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.

<!-- LOVABLE:END -->

- Store uploaded soil reports as immutable CDN assets and extracted measurements as a typed static dataset; this public reference workspace needs no account or database.
- Compute analysis from reported measurements only and keep experimental depth profiles separate from regular farm sample averages; this prevents mixing incomparable observations.
- Render original report PDFs with a browser-loaded PDF.js reader; this avoids relying on new tabs or built-in PDF support in embedded previews.
- District selections share a full-viewport reader workspace with separate regular-report and experimental-report subsections; switching districts resets search and category so documents never leak between scopes.
