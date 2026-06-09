# clearpath-docs

Public-facing legal documents for the ClearPath personal finance app.
Served via GitHub Pages at https://yungwhitley.github.io/clearpath-docs/

## Contents

- `privacy.html`: Privacy Policy
- `terms.html`: Terms of Service
- `support.html`: Support page (FAQ + contact email)
- `index.html`: Landing page linking to the above

## Updating policies

The Privacy Policy and Terms of Service are generated via Termly's
free-tier wizard. To update:

1. Edit the policy in the Termly dashboard
2. Open the updated policy's preview, then View Page Source
3. Copy the rendered HTML
4. Replace the `<body>` content in `privacy.html` (or `terms.html`)
   below the wrapper `<style>` block, keeping the surrounding HTML5
   doctype + `<head>` + closing tags intact
5. Commit and push; GitHub Pages redeploys within a minute or two
