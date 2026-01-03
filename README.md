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
| nwg-bar                    | https://github.com/nwg-piotr/nwg-bar                            | :heavy_check_mark: |
| nwg-clipman                | https://github.com/nwg-piotr/nwg-clipman                        | :heavy_check_mark: |
| nwg-displays               | https://github.com/nwg-piotr/nwg-displays                       | :heavy_check_mark: |
| nwg-dock                   | https://github.com/nwg-piotr/nwg-dock                           | :heavy_check_mark: |
| nwg-dock-hyprland          | https://github.com/nwg-piotr/nwg-dock-hyprland                  | :heavy_check_mark: |
| nwg-drawer                 | https://github.com/nwg-piotr/nwg-drawer                         | :heavy_check_mark: |
| nwg-hello                  | https://github.com/nwg-piotr/nwg-hello                          | :heavy_check_mark: |
| nwg-icon-picker            | https://github.com/nwg-piotr/nwg-icon-picker                    | :heavy_check_mark: |
| nwg-launchers              | https://github.com/nwg-piotr/nwg-launchers                      | :heavy_check_mark: |
| nwg-look                   | https://github.com/nwg-piotr/nwg-look                           | :heavy_check_mark: |
| nwg-menu                   | https://github.com/nwg-piotr/nwg-menu                           | :heavy_check_mark: |
| nwg-panel                  | https://github.com/nwg-piotr/nwg-panel                          | :heavy_check_mark: |
| nwg-readme-browser         | https://github.com/nwg-piotr/nwg-readme-browser                 | :heavy_check_mark: |
| nwg-shell                  | https://github.com/nwg-piotr/nwg-shell                          | :heavy_check_mark: |
| nwg-shell-config           | https://github.com/nwg-piotr/nwg-shell-config                   | :heavy_check_mark: |
| nwg-shell-wallpapers       | https://github.com/nwg-piotr/nwg-shell-wallpapers               | :heavy_check_mark: |
| python3-dasbus             | https://github.com/dasbus-project/dasbus                        | :heavy_check_mark: |
| python3-geographiclib      | https://github.com/geographiclib/geographiclib-python           | :x: |
| python3-imageio-ffmpeg     | https://github.com/imageio/imageio-ffmpeg                       | :heavy_check_mark: |
| python3-screeninf0         | https://github.com/rr-/screeninfo                               | :heavy_check_mark: |
| python3-geopy              | https://github.com/geopy/geopy                                  | :heavy_check_mark: |
| runkit                     | https://github.com/Letdown2491/runkit                           | :heavy_check_mark: |
| nebula-gtk                 | https://github.com/Letdown2491/nebula-gtk                       | :heavy_check_mark: |
| waypaper                   | https://github.com/anufrievroman/waypaper                       | :heavy_check_mark: |

### TODO

- [x] Build and package Xlibre once a new version is released via GitHub Actions
- 
