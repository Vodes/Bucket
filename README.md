# Vodes' Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/Vodes/Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available Tools
- opus-tools-rarewares (from [rarewares](https://www.rarewares.org/opus.php) because they're more uptodate than official builds)
- fdkaac
- dgindexnv
- Airshipper (Launcher for [veloren](https://veloren.net))

## Vapoursynth Stuff 
Very cursed implementations
- vs-dfttest2 (this is the python wrapper, install vs-dfttest2-cpu or vs-dfttest2-cuda to get a runtime)
- [vs-mlrt](https://github.com/AmusementClub/vs-mlrt)-cuda 


## How do I install apps/tools from here?

```pwsh
scoop bucket add vodes https://github.com/Vodes/Bucket
scoop install vodes/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
