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
