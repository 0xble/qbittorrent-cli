# Local fork notes

- Upstream: `ludviglundgren/qbittorrent-cli`
- Fork: `0xble/qbittorrent-cli`
- Maintained branch: `main`
- Upstream-sync branch: `master`
- Install path: `~/.local/bin/qbt`
- Install entrypoint: `bin/upgrade`
- Runtime verification: `bin/smoke`

Current fork intent:

- keep `master` close to upstream for sync
- carry fork-only runtime wiring on `main`
- stamp the installed `qbt` binary from the `v2.2.0` upstream base with a fork suffix
