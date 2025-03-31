rsbuild-issue-4294
========
Minimal error reproduction for [rsbuild#4294](https://github.com/web-infra-dev/rsbuild/issues/4924)

```console
$ pnpm rsbuild build

$ cat dist/index.html
<head><title>Rsbuild App</title><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><script defer src="/static/js/index.1d7cc275.js"></script><link href="/static/css/index.54800c1b.css" rel="stylesheet"></head><!doctype html><div id=root></div>

# The above is invalid HTML5
```
