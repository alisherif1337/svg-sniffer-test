# Next.js image optimizer content-type sniffer test fixtures

Authorized security research fixtures. Each `.png` here contains a benign SVG
(a plain red square) with a different leading-byte prefix, used to compare
Next.js's `detectContentType()` (magic bytes anchored at offset 0) against
libvips' SVG loader (scans for `<svg` within the first 1000 bytes).

No exploit code. No payloads. Temporary; will be deleted.
