# Vodes' Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/Vodes/Bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Vodes/Bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available Tools
- opus-tools-mt (from [muxtools-binaries](https://github.com/Vodes/muxtools-binaries) because they're more up-to-date than official builds)
- [fdkaac](https://github.com/nu774/fdkaac) (also via [muxtools-binaries](https://github.com/Vodes/muxtools-binaries))
- Airshipper (Launcher for [veloren](https://veloren.net))
- [SupMover](https://github.com/MonoS/SupMover)
- [ModOrganizer2](https://github.com/ModOrganizer2/modorganizer)
- [ffmpeg-ytdlp-nonfree](https://github.com/Vodes/FFmpeg-Builds)
- [dlss-swapper](https://github.com/beeradmoore/dlss-swapper)
- [CUETools](https://github.com/gchudov/cuetools.net)

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
