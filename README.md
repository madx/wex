# wex

`wex` is a text expander and generic command executor for Linux using [`wofi`](https://sr.ht/~scoopta/wofi/) and configured through a JSON file.

## Installation

- `wex` requires [`jq`](https://jqlang.github.io/jq/) and [`wl-clipboard`](https://jqlang.github.io/jq/).
- Clone this repo and create a symlink to `wex` in a folder that's in your `$PATH`.
- Create a config file at `$XDG_CONFIG_HOME/wex/wex.json`. You can copy the example config from the repo.
