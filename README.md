# Scoop Apps by ltGuillaume

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/ltguillaume/schep/actions/workflows/ci.yml/badge.svg)](https://github.com/ltguillaume/schep/actions/workflows/ci.yml) [![Excavator](https://github.com/ltguillaume/schep/actions/workflows/excavator.yml/badge.svg)](https://github.com/ltguillaume/schep/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh) with custom(ized) manifests for increased portability, specific application flavors or otherwise missing applications.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add schep https://github.com/ltguillaume/schep
scoop install schep/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
