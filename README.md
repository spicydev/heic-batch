# heic-batch

A fast, parallel CLI tool for converting Sony RAW (.ARW) images to HEIC on macOS, with metadata preservation and CPU-aware processing.

---

## 🚀 Features

- ⚡ Parallel conversion using GNU parallel
- 🧠 Auto-detects CPU cores (uses half by default)
- 🧯 Skips already converted files (safe re-runs)
- 📦 Preserves metadata using exiftool
- 🍎 Uses native macOS `sips` for HEIC conversion
- 📊 Progress bar + ETA support

---

## 📦 Requirements

Make sure these are installed:

```sh
brew install parallel exiftool