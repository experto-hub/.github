# Experto Hub organization profile

This repository publishes the content shown on the
[Experto Hub organization page](https://github.com/experto-hub).

The public profile source is [`profile/README.md`](profile/README.md).

`.experto/repository.yaml` describes this repository's documentation and
workflow facts. On pull requests and pushes to `main`, the local public baseline
checks out the exact candidate and checks its Git diff for whitespace errors.
This minimal check does not run the private central V/S/C workflows or scan
commit history for secrets. Review the source and current repository settings
separately; the declaration and a green baseline do not grant release authority.
