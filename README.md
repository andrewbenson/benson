# benson.vc

Personal website built with [Hugo](https://gohugo.io/) and the [Congo](https://github.com/jpanther/congo) theme.

## Notes

- `static/js/data.js` is the PostHog analytics snippet. It's kept as a separate static file (rather than inline in a template) because Hugo's minifier mangles the PostHog script. It's loaded lazily via `layouts/partials/head.html`.
