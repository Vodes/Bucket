# Vodes' Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/Vodes/Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available Tools
- opus-tools-rarewares (from [rarewares](https://www.rarewares.org/opus.php) because they're more uptodate than official builds)


## How do I install apps/tools from here?

```pwsh
scoop bucket add Vodes https://github.com/Vodes/Bucket
scoop install Vodes/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
