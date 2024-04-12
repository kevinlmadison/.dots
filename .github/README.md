<p align=center><img src=https://raw.githubusercontent.com/kevinlmadison/.dots/template/.github/assets/dots.png alt=".dots logo" height=100px/></p>

## (.dots) [![this is currently](https://github.com/kevinlmadison/.dots/actions/workflows/flake.yml/badge.svg?branch=main)](https://github.com/kevinlmadison/.dots/actions/workflows/flake.yml)

**so** you want to steal _my_ `.dots`? that's cool, and in fact encouraged. feel free to [use this as template](https://github.com/kevinlmadison/.dots/generate), i just ask you leave a star. my current systems are provisioned on [main](https://github.com/kevinlmadison/.dots/tree/main).

### installation

 > **Note**
 > [first template this repository](https://github.com/kevinlmadison/.dots/generate), do **not** include additional branches, and continue reading from your new repository.

if you just want my `.dots` run `setup.sh`. if you want the whole os experience, start with [a generated live disk](https://github.com/kevinlmadison/.dots/actions/workflows/iso.yml) or

```bash
nix run github:kevinlmadison/.dots#live; # make your own install disk (recommended)
# or
nix run github:kevinlmadison/.dots#home; # install with home-manager
# or
nix run github:kevinlmadison/.dots#install; # disk level installation
```

to create a live disk without `nix`:

```bash
docker run --rm -it -v/tmp:/tmp --privileged ghcr.io/kevinlmadison/dots
# but TODO: remove the --privileged flag
```

and that's it. follow the wizard 🧙🏾‍♂️✨

---
<!-- anything between #examples and /examples comments will be stripped -->

### contribution

> **Warning**
> lol, i don't want your contributions. i'm only slightly joking. it's okay to have opinionated, individualized, hacky dots- and suggesting changes to my `.vimrc` is a personal attack.

**however**, if you provide changes that make the templating system and bootstrapping system better (or you just want to show me something cool), then i'd love your contributions. make sure that you are creating a pull request against [main](https://github.com/kevinlmadison/.dots/tree/main). just note, that because these are _my_ `.dots`- i might not take _your_ suggestions. that's why i recommend [templating](https://github.com/kevinlmadison/.dots/generate) over forking `:)`

### need help? [here's help.](https://github.com/kevinlmadison/.dots/blob/template/scripts/messages/help.md)
