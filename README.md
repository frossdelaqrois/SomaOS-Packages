# SomaOS Packages

Public, signed Fedora RPM and AppStream repository for SomaOS.

## Fedora setup

Install the repository definition:

```bash
sudo curl -fsSL \
  https://frossdelaqrois.github.io/SomaOS-Packages/somaos.repo \
  -o /etc/yum.repos.d/somaos.repo
sudo dnf makecache
```

Packages then appear in KDE Discover and can also be installed with DNF:

```bash
sudo dnf install soma-unreal-manager
```

The repository signing key fingerprint is:

```text
F6E5 B513 B025 DAF6 575A 7CAA 8FC7 9C39 859F 07EB
```

Package source and SomaOS image configuration live in the private SomaOS
source repository. This public repository contains signed distributable
artifacts and catalog metadata only.
