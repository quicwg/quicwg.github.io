# QUIC WG website source

This is the repository that backs https://quicwg.org/staging.quicwg.github.io/.
Contributions in accordance with our [policies](CONTRIBUTING.md) are welcome.

## Technical Overview

The website relies on the standard [GitHub Pages](https://pages.github.com/)
workflow. Content is written in GitHub-flavoured markdown and presentation is
dealt with via
[Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/).

The front page of the website is [index.md](index.md). It relies on the layout
[`front`](_layouts/front.html).

Each sub-page is an individual markdown file (e.g.
[implementations.md](implementations.md)), which share the layout
[`subpage`](_layouts/subpage.html).

Assets such as images are located under the `asset` directory.

## FAQ

### How do I add content to an existing page?

First, identify the page you'd like to update. Then open a PR against the
related markdown. For example, if you'd like to update the [Implementations and
Tools](https://quicwg.org/staging.quicwg.github.io/implementations) page, then
you'll want to edit [implementations.md](implementations.md).

Changes to existing pages should follow the style and structure of existing
content. For example, populating the the same fields, in the same order, using
similar editorial conventions.

GitHub supports in-browser editing of existing files. Pull requests can be
created using the Edit (✏) button.

### How do I add a new page?

First, it is recommended to open an Issue to propose the new page and allow
discussion independent of any contents. This will allow us to get a better
understanding of the intent of the addition and whether it might fit within the
existing website structure.

If it is agreed that a new page should be added, then open a PR to add a new
markdown file to the root directory. This file should have a simple, short,
lowercase name with an `.md` file extension.

### Who maintains this repository? / Who is editor in chief?

Presently, the QUIC WG Chairs are the maintainers / editors of this repository
on behalf of the QUIC community operating under the IETF "Note Well". See our
[policies](CONTRIBUTING.md) for more details.

### What are the expected timelines for responding to issues or PRs?

The maintainers will do their best to respond in a timely manner. It is expected
that most issues or PRs can be dealt with pretty quickly. However, there are no
formal response time commitments.