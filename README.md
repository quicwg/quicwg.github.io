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