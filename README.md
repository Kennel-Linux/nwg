# Void Linux Software Repository

![Security Audit](https://img.shields.io/github/actions/workflow/status/Letdown2491/waypoint-gtk/security.yml?label=Security%20Audit&logo=github)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Void%20Linux-478061?logo=linux)

> [!NOTE]
>>  _How to use_
>>> _type in the terminal_

```shell
printf "repository=https://github.com/Kennel-Linux/nwg/releases/latest/download/\n" | sudo tee /etc/xbps.d/nwg-repository.conf
```

> [!IMPORTANT]
> 
> _Then type in the terminal `sudo xbps-install -S` and accept the fingerprint (Y)_

```shell
sudo xbps-install -S
```

_These packages will now be in your **OctoXBPS** package manager. When a new version of the packages is released, you will update it along with all the other packages._

You should now be able search through all nwg related packages provided by this repository, and install packages as usual:

```shell
sudo xbps-query -Rs nwg
```

<img width="933" height="697" alt="Снимок экрана_20260101_231209" src="https://github.com/user-attachments/assets/d3aa7a77-a883-4ff6-966e-a59998428a46" />

# Available packages
| package | source | automatic update |
|:--------|:-------|:-----------------|
| nwg                                 | https://github.com/nwg-piotr/           | :heavy_check_mark: |


### TODO

- [x] Build and package Xlibre once a new version is released via GitHub Actions
- 
