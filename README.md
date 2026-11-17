# Theia IDE Snap Package

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/theia-ide)

## Install [![theia-ide](https://snapcraft.io/theia-ide/badge.svg)](https://snapcraft.io/theia-ide)

```
sudo snap install theia-ide --classic
```

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Theia IDE Next

Pre-release builds of the Theia IDE, built from the latest development state every weekday and published from [`next/snap/snapcraft.yaml`](next/snap/snapcraft.yaml). They can be installed alongside the stable snap.

```
sudo snap install theia-ide-next --classic
```

## Development
```
snapcraft
sudo snap install theia-ide*.snap --dangerous --classic
```

For the next package, build from the `next` directory:
```
cd next && snapcraft
sudo snap install theia-ide-next*.snap --dangerous --classic
```
