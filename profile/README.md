<p align="center">
  <img src="https://nafphp.github.io/docs/assets/naf-logo-small-square.png" alt="NAF" width="160">
</p>

<p align="center">
  <strong>NixPHP is now NAF — “Not Another Framework”.</strong><br>
  Everything here has moved to <a href="https://github.com/nafphp">github.com/nafphp</a>.
</p>

---

## Why

The old name collided with [NixOS](https://nixos.org) — in search results, in conversation,
and most concretely in the shell, where the CLI binary was literally `nix` and could not be
called at all on a machine that had Nix installed.

## What moved where

| | |
| --- | --- |
| Composer vendor | `nixphp/…` → `naf/…` |
| GitHub organisation | `nixphp` → [`nafphp`](https://github.com/nafphp) |
| PHP namespace | `NixPHP\` → `Naf\` |
| Plugin package type | `nixphp-plugin` → `naf-plugin` |
| CLI binary | `nix` → `naf` |
| Documentation | [nafphp.github.io/docs](https://nafphp.github.io/docs/) |

A plugin still declaring `nixphp-plugin` is **not loaded** by NAF — silently, with no error.
The [upgrade guide](https://nafphp.github.io/docs/upgrading-from-nixphp/) covers the whole
move in one page, including a `sed` line for the namespace.

## The packages

`naf/framework`, and the plugins around it: `view`, `form`, `session`, `database`, `orm`,
`i18n`, `cli`, `mail`, `client`, `queue`, `schedule`, `auth`, `oauth-client`, `oauth-server`
and `mcp`. Start with
**[What do I actually need?](https://nafphp.github.io/docs/choosing-packages/)**

```bash
composer create-project naf/app my-app
```

## This organisation

Every repository here is archived and read-only. The `nixphp/*` packages stay on Packagist so
existing installations keep working, and they receive no further releases. The old
documentation site has been retired.
