# homebrew-rowt

Homebrew tap for [`rowt`](https://github.com/tanghong123/rowt) — split traffic
three ways on macOS (personal VLESS/AnyTLS tunnel, corporate VPN, or direct)
from one local sing-box proxy that coexists with the corp VPN.

```sh
brew tap tanghong123/rowt
brew install rowt
```

> While the `rowt` repo is private, `brew install` needs a GitHub token with
> access — set `HOMEBREW_GITHUB_API_TOKEN` (e.g. `export
> HOMEBREW_GITHUB_API_TOKEN="$(gh auth token)"`). Once `rowt` is public, no
> token is needed.

Then:

```sh
rowt fetch      # download sing-box
rowt onboard    # guided setup
```
