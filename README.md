# summa-docs

Public-facing legal documents for the Summa personal finance app.
Served via GitHub Pages at https://yungwhitley.github.io/summa-docs/

## Contents

- `privacy.html`: Privacy Policy
- `terms.html`: Terms of Service / EULA (also linked from App Store Connect as the Custom EULA)
- `support.html`: Support page (FAQ + contact email)
- `index.html`: Landing page linking to the above

## Updating policies

The Privacy Policy and Terms of Service are generated via Termly's
free-tier wizard. The brand name in Termly should be set to `Summa`.

To update:

1. Edit the policy in the Termly dashboard.
2. Open the updated policy's preview, then View Page Source.
3. Copy the rendered HTML.
4. Replace the `<body>` content in `privacy.html` (or `terms.html`)
   below the wrapper `<style>` block, keeping the surrounding HTML5
   doctype + `<head>` + closing tags intact.
5. Commit and push; GitHub Pages redeploys within a minute or two.

> Heads-up: this repo was renamed from `clearpath-docs` to `summa-docs`
> as part of the brand rename. Any in-place edits replacing "ClearPath"
> with "Summa" will be overwritten the next time you regenerate from
> Termly unless the brand name is updated in Termly first.

## Brand casing

`Summa` is capitalized in all prose. Lowercase `summa` is only used for
the wordmark / logo, not for body text. These legal documents are prose
and should all use `Summa`.
