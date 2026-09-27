# mAIstro studio sounds

Multisampled instruments for [mAIstro](https://github.com/atscglobal-ie/mAIstro)'s backing band,
converted to lossless FLAC with a JSON manifest per instrument:

- `v1/`: drums, basses, piano and electric guitars (10 instruments, about 0.9 GB).
- `v2/`: everything in v1 plus strings, brass, woodwinds, saxophones, harmonicas, keyboards and
  organs, mallets, folk instruments, three more drum kits, timpani and percussion (55 instruments,
  about 2.2 GB). The current pack. The app downloads them on demand (Settings → Studio sounds) or installs them with the
Windows dev host.

Every sample here comes from a library released under **CC0 1.0** (public domain dedication), and
this collection is released under CC0 1.0 too. See `NOTICE.md` for the sources and credits.

Layout: `v<pack version>/pack.json`, then `v<n>/<instrument>/manifest.json` and its `.flac` files.
Built by `pnpm studio-pack` in the mAIstro repo; do not edit by hand.
