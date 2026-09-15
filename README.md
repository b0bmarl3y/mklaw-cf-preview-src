# Temporary MKLaw CF preview source drop

Anonymous fetch for the shared box (no GitHub token). Delete this repo after Elon pulls.

## Direct zip (verified)

```bash
curl -L -o mklaw-next-cf-preview.zip https://litter.catbox.moe/dtw4b8.zip
sha256sum mklaw-next-cf-preview.zip
# expect: b1fc21cd1114b5d16e08079137fbab859252f8b26b19bf6c6074fbb04680042a
unzip mklaw-next-cf-preview.zip
cd app && bun install && bun run cf:deploy   # after D1 id is wired
```

- URL: https://litter.catbox.moe/dtw4b8.zip
- Size: 31724371 bytes
- SHA-256: `b1fc21cd1114b5d16e08079137fbab859252f8b26b19bf6c6074fbb04680042a`
- Source commit: `ace2bcc` (no secrets, no dist, no node_modules)
- Hosted on litterbox ~72h from 2026-09-15 23:39 UTC

This repository is a pointer only. The private `mklaw-next` release 404s without a token. PR #1 was not merged.
