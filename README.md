# Portable Linux Apps — Material You sample

A sample of the [Portable Linux Apps](https://portable-linux-apps.github.io/)
home page rebuilt with [mdui 2](https://www.mdui.org) (Material You).

- `index.html` — self-contained preview: mdui and Material Icons load from their
  CDNs, while the asciinema player, the `.cast` recordings, the app icons and the
  favicon are inlined. This is the file GitHub Pages serves.
- `index.mdui.html` — the same page with relative asset paths, as committed in the
  source checkout (it expects the repository assets next to it).

The page is derived from `index.in` in
[Portable-Linux-Apps/Portable-Linux-Apps.github.io](https://github.com/Portable-Linux-Apps/Portable-Linux-Apps.github.io)
(MIT). Links to generated pages (`apps.html`, `ai.html`, `/en/app/…`) and the
`apps.json` fetch resolve only on the real site, so here they fall back to the
inlined demo data.
