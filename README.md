# client-previews

Public-facing client preview surfaces for [Boco Agency](https://boco.agency).

Each subdirectory holds the in-flight documents for one client. Documents are self-contained static HTML with embedded feedback channels (mailto-based today; cockpit-integrated in v2).

## Live

- **Index**: https://abhishekjajodia.github.io/client-previews/
- **Vara FAQ Science Tab**: https://abhishekjajodia.github.io/client-previews/vara/faq-science-tab.html

## Adding a new preview

1. Drop the HTML under `{brand}/{doc-slug}.html`
2. Add a card to `index.html`
3. Commit + push to `main` — GitHub Pages auto-deploys

## Feedback channel

Each preview embeds three `mailto:` buttons (Approve / Request changes / Comment). Responses land at `abhishek@boco.vc` and are triaged into the cockpit thread for the relevant brand.
