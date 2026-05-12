# looties-io.github.io

Source for the public Looties developer page at [looties-io.github.io](https://looties-io.github.io).

This is a static landing page that links to the [Looties marketplace](https://looties.io), surfaces the open-source [looties-skills](https://github.com/looties-io/looties-skills) collection, and serves as the public face of the [`looties-io`](https://github.com/looties-io) GitHub organization.

## Editing

Edit `index.html` directly. No build step, no framework. Push to `main` and GitHub Pages redeploys.

## Stack

- Plain HTML + inline CSS — target page weight under 50 KB.
- `Organization` JSON-LD schema in `<head>` for rich-result eligibility.
- Brand colors and typography match [looties.io](https://looties.io).

## Future

When this page grows beyond a landing surface (docs hub, dev signup, public roadmap with real traffic), migrate to `dev.looties.io` via a `CNAME` file + custom domain in Pages settings.
