# Contributing

Thanks for helping improve Leverprice.

## Issues

Search existing issues first. For a bug, include the SDK and its version, your runtime and framework, what you expected and what happened. Never paste secret keys, cookies or customer data.

## Pull requests

- Keep each pull request to one change. For anything larger than a fix, open an issue first.
- Run the repository's tests and linters before you push. CI runs the same checks.
- Files in `conformance/` come from the Leverprice server and are shared by every SDK. Do not edit them by hand; if a vector looks wrong, open an issue.
- Every SDK behaves the same way. A change to how prices, cookies or signatures work starts in the protocol spec.

By contributing, you agree that your work is released under the repository's license.
