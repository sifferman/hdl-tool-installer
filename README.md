# HDL Tool Installer

## About

This script downloads all the latest releases for all the open source HDL CAD tools.

## Help

```plain
Usage: ./install <installation_directory> [options]
Options:
    --oss-cad-suite
    --synlig
    --zachjs-sv2v
    --verible
```

## Downloading

```bash
curl -sSL https://raw.githubusercontent.com/sifferman/hdl-tool-installer/main/install | bash -s -- <build_dir> --oss-cad-suite --synlig --zachjs-sv2v --verible
```
