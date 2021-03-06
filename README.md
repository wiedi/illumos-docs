# illumos.org

This repository contains markdown for illumos.org. It is written in
[mkdocs](http://www.mkdocs.org).

We are using the [material](https://squidfunk.github.io/mkdocs-material/)
theme.

## Contributing 

If you're looking to help out but aren't sure where to start, please have a
look at our [open issues](https://github.com/illumos/docs/issues).

### Installing mkdocs

`mkdocs` is written in Python. Please see their
[instructions](http://www.mkdocs.org/#installation) for details, but the short
of it is:

```
pip install mkdocs
pip install mkdocs-material
pip install markdown-include
```

### Testing changes

Clone this repo. Create a topic branch. Make your changes.

Assuming you have `mkdocs` installed, you can simply do `mkdocs serve` to start
a local test server.

```
19:37:47 cronus:~/src/illumos/docs$ mkdocs serve
INFO    -  Building documentation...
INFO    -  Cleaning site directory
[I 180302 19:37:52 server:283] Serving on http://127.0.0.1:8000
[I 180302 19:37:52 handlers:60] Start watching changes
[I 180302 19:37:52 handlers:62] Start detecting changes
```

### Submitting changes

Additions or updates should be submitted via Pull Request.

If you notice any problems, but don't feel like you want to fix them yourself,
please open an [issue](https://github.com/illumos/docs/issues).

