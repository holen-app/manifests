# Holen Manifests

These are manifests and supporting files for use with the
[holen](https://github.com/justone/holen) utility fetcher.

# Quick Start

1. Clone this repository: `git clone https://github.com/justone/holen.git`
2. Add the bin path to your PATH: `export PATH=$PATH:$PWD/holen-manifests/bin`
3. Run any utility by just typing its name.

Examples:

* Latest version of jq: `jq`
* Version 1.4 of jq: `jq--1.4`

# Selecting a different strategy:

By default, holen tries strategies in the following order:

1. Docker
2. Binary

If you'd like it to try binary first, just run `holen config strategy.priority binary,docker`.
