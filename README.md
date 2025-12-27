# blueprint

* Forked from the [numtide](https://numtide.com) [project](https://github.com/numtide/blueprint).

blueprint is an opinionated library that maps a standard folder structure to flake outputs, allowing you to divide up your flake into individual files across these folders.

## Features

Support for:

* NixOS
* default RFC166 nix formatter with `nix fmt`
* supports overridable systems with [nix-systems](https://github.com/nix-systems).
* automatic flake checks from packages and NixOS configurations.

## Quickstart

1. [Install Nix](https://nix.dev/install-nix) or use NixOS.
2. Run `mkdir my-project && cd my-project`
3. Run `nix flake init -t github:philiptaron/blueprint`
