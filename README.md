# Sort legal documents

The Terms of Service, Privacy Policy and Cookie and Device Storage Policy for the Sort app, published by Sort App Ltd and served as plain pages through GitHub Pages so that the App Store and Play Store listings, and the documents themselves, can link to a stable, tracker-free address.

- `terms.md` → `/legal/terms`
- `privacy.md` → `/legal/privacy`
- `cookies.md` → `/legal/cookies`

## Updating a document

Edit the Markdown file on `main` and commit. GitHub Pages rebuilds the site in about a minute; the address does not change.

## Custom domain

To serve these pages at `legal.sortapp.co.uk`, first add a CNAME record at the registrar pointing `legal` to `sort-app.github.io`, then add a `CNAME` file containing `legal.sortapp.co.uk` to this repository. Do not add the file before the DNS record exists or the github.io links stop working.

## Rights

Content © Sort App Ltd. All rights reserved. No licence is granted to reuse the text.
