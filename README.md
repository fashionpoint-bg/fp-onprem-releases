# fp-onprem — Release artifacts

Public mirror of the signed Windows installer of fp-onprem, the program through which
FashionPoint prints receipts on a clinic's fiscal printer.

**Source code:** [`fashionpoint-bg/fp-onprem`](https://github.com/fashionpoint-bg/fp-onprem) (private)

This repository hosts only the signed installers. GitHub Releases inherit the visibility of their
repository, so clinics cannot download them from the private source repository.

Every release carries the installer twice, as `FashionPoint-Setup-<version>.exe` and as
`FashionPoint-Setup-Windows-x64.exe`, so that

    https://github.com/fashionpoint-bg/fp-onprem-releases/releases/latest/download/FashionPoint-Setup-Windows-x64.exe

always gives the latest version; FashionPoint's clinic admin links there. `SHA256SUMS` lists both
files.

The installer connects a computer to a clinic only with a one-time code that a FashionPoint
platform admin issues in the clinic's profile.
