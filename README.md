# Policy Builder demo: nginx web server

This repository is an example of the policy CFEngine Policy Builder generates: a visual demo project
that installs and configures nginx and publishes a landing page, saved to disk exactly as the app
writes it. It's an ordinary cfbs project, with one module per top-level policy file and the
templates in `templates/`, so you can read, build and deploy it like a hand-written one. The
builder's own editor data lives under `meta` in `cfbs.json`. The `.png` files show the canvases the
policy was built from.
