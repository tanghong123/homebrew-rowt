# homebrew-rowt

Homebrew tap for [`rowt`](https://github.com/tanghong123/rowt) — split traffic
three ways on macOS (personal VLESS/AnyTLS tunnel, corporate VPN, or direct)
from one local sing-box proxy that coexists with the corp VPN.

```sh
brew tap tanghong123/rowt
brew install rowt
```

Then:

```sh
rowt fetch      # download sing-box
rowt onboard    # guided setup
```
