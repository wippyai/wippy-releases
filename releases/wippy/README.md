# Wippy Releases

This repository contains pre-built binaries for the Wippy runtime, organized by branch and release type.

## Quick Access

- **Main Branch**: [wippy/main](./main/) - Latest stable builds
- **Develop Branch**: [wippy/develop](./develop/) - Latest development builds
- **Latest Build**: [wippy/latest](./latest/) - Most recent build (any branch)

## Current Build

- **Build**: [wippy/feature/2025-09-26-16-14](./wippy/feature/2025-09-26-16-14/) (Commit: dc807194)
- **Branch/Tag**: 125/merge
- **Date**: 2025-09-26 16:14:06 UTC

## Available Platforms

- **Linux AMD64**: Optimized for x86_64 Linux systems
- **Linux ARM64**: Optimized for ARM64 Linux systems (Raspberry Pi, etc.)
- **Windows AMD64**: Optimized for x86_64 Windows systems
- **macOS AMD64**: Optimized for Intel-based Mac systems
- **macOS ARM64**: Optimized for Apple Silicon Mac systems (M1/M2/M3)

## Binary Optimization

All binaries are optimized for minimal size:
- **Build optimization**: Stripped debug symbols, trimmed paths, PIE build mode
- **UPX compression**: ~80% size reduction with LZMA compression
- **Final size**: ~12MB (down from ~78MB uncompressed)

## Quick Start

### Main Branch (Stable)
```bash
# Download latest stable build
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/main/wippy-linux-amd64
chmod +x wippy-linux-amd64
./wippy-linux-amd64 --help
```

### Develop Branch (Development)
```bash
# Download latest development build
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/develop/wippy-linux-amd64
chmod +x wippy-linux-amd64
./wippy-linux-amd64 --help
```

### Latest Build (Any Branch)
```bash
# Download most recent build
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/latest/wippy-linux-amd64
chmod +x wippy-linux-amd64
./wippy-linux-amd64 --help
```

### Windows
```powershell
# Download latest build (Windows)
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/latest/wippy-windows-amd64.exe" -OutFile "wippy-windows-amd64.exe"
.\wippy-windows-amd64.exe --help
```

### macOS
```bash
# Download latest build (macOS)
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/latest/wippy-darwin-amd64  # Intel Mac
# or
wget https://raw.githubusercontent.com/wippyai/wippy-releases/main/releases/wippy/latest/wippy-darwin-arm64  # Apple Silicon Mac
chmod +x wippy-darwin-amd64
./wippy-darwin-amd64 --help
```

## Directory Structure

- **wippy/main/**: Latest builds from main branch (stable)
- **wippy/develop/**: Latest builds from develop branch (development)
- **wippy/releases/**: Timestamped releases from version tags
- **wippy/feature/**: Timestamped builds from feature branches (YYYY-MM-DD-HH-MM format)

## Build History

All builds are preserved in their respective directories. Check the [releases directory](./) for historical builds.
