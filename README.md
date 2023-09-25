# Scoop Apps by ltGuillaume

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/ltguillaume/schep/actions/workflows/ci.yml/badge.svg)](https://github.com/ltguillaume/schep/actions/workflows/ci.yml) [![Excavator](https://github.com/ltguillaume/schep/actions/workflows/excavator.yml/badge.svg)](https://github.com/ltguillaume/schep/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh) with custom(ized) manifests for increased portability, specific application flavors or otherwise missing applications.

## How do I install these manifests?

To add this bucket to Scoop, run the following:
```pwsh
scoop bucket add schep https://github.com/ltguillaume/schep
```

Then, you can install an application via:
```pwsh
scoop install schep/<manifestname>
```

This bucket is also indexed at https://scoop.sh.

## Update tip

Create a new shortcut (.lnk file) with the following command to quickly update all apps and clean up Scoop:
```cmd
cmd.exe /k scoop update update * && scoop cleanup * && scoop cache rm * && pause && exit
```
