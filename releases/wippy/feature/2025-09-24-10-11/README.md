# Wippy Build 35605353

**Build Date**: 2025-09-24 10:11:39 UTC
**Commit**: 35605353795cb1bce31a30fe3eca6fbe6b30c433
**Branch/Tag**: 125/merge
**Pipeline**: 17973217984
**Directory**: wippy/feature/2025-09-24-10-11

## Downloads

This build contains the following optimized binaries (available for direct download):

- **Linux AMD64**: [wippy-linux-amd64](./wippy-linux-amd64) (compressed with UPX)
- **Linux ARM64**: [wippy-linux-arm64](./wippy-linux-arm64) (compressed with UPX)
- **Windows AMD64**: [wippy-windows-amd64.exe](./wippy-windows-amd64.exe) (compressed with UPX)



## Binary Optimization

All binaries are optimized for minimal size:
- **Build optimization**: Stripped debug symbols, trimmed paths, PIE build mode
- **UPX compression**: ~80% size reduction with LZMA compression
- **Final size**: ~12MB (down from ~78MB uncompressed)

## Installation

### Linux
```bash
# Download and make executable
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-24-10-11/wippy-linux-amd64
chmod +x wippy-linux-amd64
./wippy-linux-amd64 --help
```

### Windows
```powershell
# Download and run
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-24-10-11/wippy-windows-amd64.exe" -OutFile "wippy-windows-amd64.exe"
.\wippy-windows-amd64.exe --help
```

## Verification

Verify the integrity of downloaded files using the provided checksums:
```bash
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-24-10-11/checksums.txt
sha256sum -c checksums.txt
```

## Build Information

- **Repository**: wippyai/runtime
- **Workflow**: [View Build](https://github.com/wippyai/runtime/actions/runs/17973217984)
- **Source**: [Commit 35605353](https://github.com/wippyai/runtime/commit/35605353795cb1bce31a30fe3eca6fbe6b30c433)
