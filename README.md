# slawrensen.github.io

Personal landing page and docs hub, served at
[docs.slawrensen.com](https://docs.slawrensen.com/).

This user-site repo owns the `docs.slawrensen.com` custom domain (see `CNAME`).
Project repos with GitHub Pages enabled appear underneath it as subpaths, for
example [`/hwinfo-streamdeck/`](https://docs.slawrensen.com/hwinfo-streamdeck/).
Adding a project is nothing more than enabling Pages on that repo; do not add a
`CNAME` to a project repo or it will try to claim the domain at the root.

`.nojekyll` keeps this a plain static page (no build step). The project docs
under each subpath run their own Jekyll build in their own repo.

Mac Sensors documentation is built from
[slawrensen/mac-sensors-streamdeck](https://github.com/slawrensen/mac-sensors-streamdeck)
and published here in `mac-streamdeck/` as static HTML, CSS, JavaScript and
images, which keeps the existing documentation URL. This directory holds
publication output only, never the product source, binaries or private records.
Review a fresh documentation build before updating it; do not copy the product
checkout into this repository.
