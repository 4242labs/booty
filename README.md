# booty

[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Maintenance](https://img.shields.io/badge/maintenance-passively--maintained-yellowgreen.svg)](CONTRIBUTING.md)

Grab-and-go artifacts from the 42labs Design System. Single source of truth — everything here is what `ds.42labs.io` serves. Function over fuss.

## What's inside

| Path | What |
|------|------|
| `tokens/` | DS design tokens (W3C-DTCG) — `.json`, `.css`, `.schema.json`. `latest` + versioned. Generated from the DS; do not hand-edit. |
| `themes/zed/` | 42labs theme for the [Zed](https://zed.dev) editor (`42labs.json`, light + dark). |
| `themes/linear/` | 42labs themes for [Linear](https://linear.app) — paste-ready custom-theme strings. |

## Use it

CDN (via jsDelivr):

```
https://cdn.jsdelivr.net/gh/4242labs/booty@main/tokens/tokens.latest.css
https://cdn.jsdelivr.net/gh/4242labs/booty@main/tokens/tokens.latest.json
```

Zed: drop `themes/zed/42labs.json` into `~/.config/zed/themes/`.

Linear: copy a string from `themes/linear/42labs-linear.md` → Settings → Preferences → Theme → Custom.

## Contributing

**Passively maintained, and closed to pull requests.** Everything here is **generated** — a
daily workflow mirrors it from the 42labs Design System, so a patch would be overwritten by
the next sync. Issues are open and are what actually get things fixed:
[open one](https://github.com/4242labs/booty/issues/new), or write to <ahoy@42labs.io>. Expect
a reply in weeks rather than days — this is not a staffed product. Details in
[CONTRIBUTING.md](CONTRIBUTING.md).

## License

[CC BY 4.0](LICENSE) — use the tokens and themes anywhere, commercial work included, and
credit 42labs. Not the fleet's usual AGPL-3.0: these are assets meant to be embedded, and
copyleft would make every use this README recommends a violation. See
[LICENSING.md](LICENSING.md).

---
If it earned its keep, [coffee is appreciated](https://buymeacoffee.com/42piratas). ☕
