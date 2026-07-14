# bagof

`bagof` is a namespace package that houses miscelaneous tools
that I found useful when implementing python packages.

The core idea behind this project is that each "bag" can be installed on
its own, and with a minimal set of dependencies (none when possible,
other bags when useful, well-known external packages only if necessary).

Another important point is to ensure compatibility with (some) older
versions of python, even if they have reached end of life. Python has a
5-year support policy for each version (2 years of bug fixes + 3 years
of security updates), which is quite short compared to most research
projects. While updating python is preferred for security reasons, it is
sometimes not possible, and I would like these users to benefit from
up-to-date versions of my tools nonetheless. Most bags will support the
same range of python versions as the most recent version of
[`typing_extensions`](https://typing-extensions.readthedocs.io/),
although some will support older versions (when possible) and some newer
only ones (when required).

## List of bags

| Module  | Description |
| ------- | ----------- |
| [`hints`](https://bagofseeds.github.io/bagof-hints/) | Reusable typing hints |
