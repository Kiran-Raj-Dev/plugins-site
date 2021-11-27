# Manim Community Plugin

Manim's plugins site, simple app with js.

## Adding a Plugin

There is a Github Actions set up to run daily which will automatically your plugin to the website if it matches with this RegEx `<(.*)>manim-(?P<name>.*)<(.*)>`. If your plugin doesn't match this RegEx, then you can make a PR adding your plugin name as how it is PyPI, to `scripts/default.json` under `extras` section.

# Code of Conduct

Our full code of conduct, and how we enforce it, can be read on [our website](https://docs.manim.community/en/latest/conduct.html).
