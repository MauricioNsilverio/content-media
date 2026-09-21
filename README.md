# content-media

Public image host for the @mauricionsilverio Instagram carousels.

Instagram's publishing API only accepts images from a public URL, so each staged carousel lands
here as `<YYYY-MM-DD>/<content-id>/NN.jpg` before its slot. The publisher (a GitHub Actions
workflow in a private repo) hands these raw URLs to Meta at 12:00 and 18:00 São Paulo.

`_probe/probe.jpg` is a blank image used to check that raw URLs are served as `image/jpeg`.

Nothing here is secret: every image is a post that is, or is about to be, public on Instagram.
