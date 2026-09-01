# archify-skill (slim mirror)

Slim mirror containing only the `archify/` skill directory from
[tt-a1i/archify](https://github.com/tt-a1i/archify) (MIT), for git skill-pack
importers with repository size limits.

- Upstream commit mirrored: `7a16d30322f5bd09c832386faa95d8c9a933f0c0`
- Mirrored: 2026-09-01
- Skill subtree: ~7.3MB, 191 files (upstream repo ~111MB packed)

## Refresh

```sh
git clone --depth 1 --filter=blob:none --sparse https://gh-proxy.com/https://github.com/tt-a1i/archify
cd archify && git sparse-checkout set archify
# copy archify/ over this repo's archify/, commit, push
```

All credit to the archify authors. See LICENSE.
