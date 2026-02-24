# Scoop Bucket for DittoFS

[Scoop](https://scoop.sh) package manifests for [DittoFS](https://github.com/marmos91/dittofs) — a modular virtual filesystem with pluggable storage backends.

## Usage

```powershell
scoop bucket add dittofs https://github.com/marmos91/scoop-bucket
scoop install dfs       # Server daemon
scoop install dfsctl    # Client CLI
```

## Available packages

| Package | Description |
|---------|-------------|
| **dfs** | DittoFS server daemon |
| **dfsctl** | DittoFS CLI client for remote server management |

## Updating

```powershell
scoop update
scoop update dfs dfsctl
```

## How it works

Package manifests in this repository are automatically published by [GoReleaser](https://goreleaser.com) on each DittoFS release. Do not edit them manually.
