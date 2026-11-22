# Why this fork

microsoft/onnxruntime-swift-package-manager disappeared from GitHub in November 2026, and
download.onnxruntime.ai (the Azure CDN its manifest pointed at) no longer serves the binaries. This
copy keeps the 1.24.2 release resolvable: the history and tags as they were, plus one commit on the
`smalt` branch (tag `1.24.2-smalt.1`) pointing the two binary targets at this repository's release assets. The
archives are Microsoft's own, byte for byte (same SHA-256 as the original manifest). MIT, see LICENSE.
