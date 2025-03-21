# gh repo-size

[GitHub-CLI](https://github.com/cli/cli) extension demo to query the size of a specified GitHub repository.
Yeah, as simple as that.
Currently, submodule is not counted.

## Prerequisites

GNU Coreutils (mostly already installed), cURL & jq.

## Quickstart

```sh
# Install
gh ext install Vinfall/gh-repo-size

# Usage, accepted styles
gh repo-size Vinfall/gh-repo-size
gh repo-size github.com/torvalds/linux
gh repo-size https://github.com/torvalds/linux
# Also possible to use bare API
gh repo-size -r torvalds/linux
gh repo-size --raw torvalds/linux

# Uninstall
gh ext remove Vinfall/gh-repo-size
```

## [License](/COPYING)

Licensed under CC0 1.0 Universal or Public Domain, whichever is more permissive.
