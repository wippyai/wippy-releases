# Wippy Releases

This repository contains official releases of the Wippy Runtime and PackCLI helper tool.

## Downloads

### Wippy Runtime

- **Windows AMD64**: wippy-windows-amd64-{version}.zip
- **Linux AMD64**: wippy-linux-amd64-{version}.tar.gz
- **Linux ARM64**: wippy-linux-arm64-{version}.tar.gz
- **macOS AMD64**: wippy-darwin-amd64-{version}.tar.gz
- **macOS ARM64**: wippy-darwin-arm64-{version}.tar.gz

### PackCLI Helper Tool

PackCLI helper tool is included within the Wippy Runtime archives.

## Installation

### Windows
```bash
# Extract the archive
unzip wippy-windows-amd64-{version}.zip

# Run the executable
wippy.exe --help
```

### Linux
```bash
# Extract the archive
tar -xzf wippy-linux-amd64-{version}.tar.gz

# Make executable and run
chmod +x wippy
./wippy --help
```

### macOS
```bash
# Extract the archive
tar -xzf wippy-darwin-amd64-{version}.tar.gz

# Make executable and run
chmod +x wippy
./wippy --help
```

## Verification

SHA256 checksums are available for each release archive.

## PackCLI Usage

PackCLI is included within the Wippy Runtime archives for module management and development tasks.

### Windows
```bash
# After extracting the archive
packcli.exe --help
packcli.exe module init my-module
```

### Linux
```bash
# After extracting the archive
chmod +x packcli
./packcli --help
./packcli module init my-module
```

### macOS
```bash
# After extracting the archive
chmod +x packcli
./packcli --help
./packcli module init my-module
```

## Archive Format

All releases are distributed as compressed archives:
- **Windows**: ZIP format (.zip)
- **Linux/macOS**: GZIP-compressed TAR format (.tar.gz)

## License

This project is licensed under the terms specified in the main repository.

---
