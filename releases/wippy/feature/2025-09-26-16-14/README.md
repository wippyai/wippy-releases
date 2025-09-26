# Wippy Build dc807194

**Build Date**: 2025-09-26 16:14:06 UTC
**Commit**: dc8071941f8c93c3d8dd1eed8c66141072539bb8
**Branch/Tag**: 125/merge
**Pipeline**: 18042988573
**Directory**: wippy/feature/2025-09-26-16-14

## Downloads

This build contains the following optimized binaries (available for direct download):

- **Linux AMD64**: [wippy-linux-amd64](./wippy-linux-amd64) (compressed with UPX)
- **Linux ARM64**: [wippy-linux-arm64](./wippy-linux-arm64) (compressed with UPX)
- **Windows AMD64**: [wippy-windows-amd64.exe](./wippy-windows-amd64.exe) (compressed with UPX)
- **macOS AMD64**: [wippy-darwin-amd64](./wippy-darwin-amd64) (compressed with UPX)
- **macOS ARM64**: [wippy-darwin-arm64](./wippy-darwin-arm64) (compressed with UPX)



## Binary Optimization

All binaries are optimized for minimal size:
- **Build optimization**: Stripped debug symbols, trimmed paths, PIE build mode
- **UPX compression**: ~80% size reduction with LZMA compression
- **Final size**: ~12MB (down from ~78MB uncompressed)

## Installation

### Linux
```bash
# Download and make executable
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-26-16-14/wippy-linux-amd64
chmod +x wippy-linux-amd64
./wippy-linux-amd64 --help
```

### Windows
```powershell
# Download and run
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-26-16-14/wippy-windows-amd64.exe" -OutFile "wippy-windows-amd64.exe"
.\wippy-windows-amd64.exe --help
```

### macOS
```bash
# Download and make executable (Intel Mac)
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-26-16-14/wippy-darwin-amd64
chmod +x wippy-darwin-amd64
./wippy-darwin-amd64 --help

# Or for Apple Silicon Mac
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-26-16-14/wippy-darwin-arm64
chmod +x wippy-darwin-arm64
./wippy-darwin-arm64 --help
```

## Verification

Verify the integrity of downloaded files using the provided checksums:
```bash
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/feature/2025-09-26-16-14/checksums.txt
sha256sum -c checksums.txt
```

## Build Information

- **Repository**: wippyai/runtime
- **Workflow**: [View Build](https://github.com/wippyai/runtime/actions/runs/18042988573)
- **Source**: [Commit dc807194](https://github.com/wippyai/runtime/commit/dc8071941f8c93c3d8dd1eed8c66141072539bb8)
