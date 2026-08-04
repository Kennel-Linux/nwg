<div align="center" markdown="1">
  <a>
   <!-- <img width="450" height="auto" alt="void-linux" src="https://github.com/Kennel-Linux/nwg/blob/main/img/void-linux.gif" /> -->	  
   <img src="https://github.com/Kennel-Linux/nwg/blob/main/img/void-linux-3.gif?raw=true" width="450" height="auto" />
  </a>
	
##### 【`Unofficial package repository`】

[![Platform](https://img.shields.io/badge/platform-Void%20Linux-478061?logo=linux&colorA=363a4f&)](#)
[![x85_64-glibc](https://img.shields.io/badge/x86__64-glibc-478061?style=badge&colorA=363a4f&)](#)

[![Build](https://img.shields.io/github/actions/workflow/status/Kennel-Linux/nwg/build-awk.yml?style=flat-square&label=BUILD&logo=githubactions&logoColor=white&colorA=363a4f&)](https://github.com/Kennel-Linux/nwg/actions)
[![Updates](https://img.shields.io/github/actions/workflow/status/Kennel-Linux/nwg/update.yml?style=flat-square&label=AUTO-UPDATE&logo=github&logoColor=white&colorA=363a4f&)](https://github.com/Kennel-Linux/nwg/actions)

[![GitHub](https://img.shields.io/github/license/Kennel-Linux/nwg?style=flat-square&label=License&colorA=363a4f&colorB=purple&logo=gitbook)](#)
[![GitHub contributors](https://img.shields.io/github/contributors/Kennel-Linux/nwg?style=flat-square&colorA=363a4f&colorB=purple&logo=github&label=Contributors)](#)
[![GitHub release (with filter)](https://img.shields.io/github/v/release/Kennel-Linux/nwg?style=flat-square&logo=github&label=Release&colorA=363a4f&colorB=purple)](https://github.com/Kennel-Linux/nwg/releases/)
[![GitHub issues](https://img.shields.io/github/issues-raw/Kennel-Linux/nwg?style=flat-square&label=Open%20Issues&logo=github&colorA=363a4f&colorB=purple)](#)
[![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/Kennel-Linux/nwg?style=flat-square&label=Closed%20Issues&logo=github&colorA=363a4f&colorB=purple)](#)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Kennel-Linux/nwg/main?style=flat-square&label=Last%20Commit&logo=github&colorA=363a4f&colorB=purple)](#)

</div>
<br>

<!-- ![Security Audit](https://img.shields.io/github/actions/workflow/status/Letdown2491/waypoint-gtk/security.yml?label=Security%20Audit&logo=github)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Void%20Linux-478061?logo=linux) -->

> [!NOTE]
>>  _How to use_
>>> _type in the terminal_

```shell
printf "repository=https://github.com/Kennel-Linux/nwg/releases/latest/download/" | sudo tee /etc/xbps.d/nwg-repository.conf
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
| python3-geographiclib      | https://github.com/geographiclib/geographiclib-python           | 🔐 |
| python3-geopy              | https://github.com/geopy/geopy                                  | :heavy_check_mark: |
| python3-imageio-ffmpeg     | https://github.com/imageio/imageio-ffmpeg                       | :heavy_check_mark: |
| python3-screeninfo         | https://github.com/rr-/screeninfo                               | 🔐 |
| runkit                     | https://github.com/Letdown2491/runkit                           | :heavy_check_mark: |
| nebula-gtk                 | https://github.com/Letdown2491/nebula-gtk                       | :heavy_check_mark: |
| waypaper                   | https://github.com/anufrievroman/waypaper                       | :heavy_check_mark: |

### TODO

- [x] Build and package nwg once a new version is released via GitHub Actions
- 

<details>
<summary><b>repo-key</b></summary>
<br/>

```
sudo mkdir -p /var/db/xbps/keys
sudo wget -O /var/db/xbps/keys/00:ca:42:57:c9:c0:9a:ec:94:b4:7d:97:e5:a9:aa:1e.plist \
  https://github.com/Kennel-Linux/nwg/raw/refs/heads/main/repo-keys/x86_64/00:ca:42:57:c9:c0:9a:ec:94:b4:7d:97:e5:a9:aa:1e.plist
```
  
> repo-key `00:ca:42:57:c9:c0:9a:ec:94:b4:7d:97:e5:a9:aa:1e.plist`

```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple Computer//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>public-key</key>
	<data>LS0tLS1CRUdJTiBQVUJMSUMgS0VZLS0tLS0KTUlJQklqQU5CZ2txaGtpRzl3MEJBUUVGQUFPQ0FROEFNSUlCQ2dLQ0FRRUF6aFR1SkVjalBFZzZaUnNGbThtLwpaRnY0RWoyNUZVZzRZR3JQZlI3cWdaaGs5MExWd1hnTnVBQVl2TXFrSmpDd1dueEdYZVNzWUgyNFpSaFhiSHNvCm1DOGJFSDBOWkpmWGRYWFl3Rjg1dGl3b0RGRkpxOE0wN3daT0JsVmI4YXhkRm96UElpWXlRUEMxN1BwTjg0UksKS3NzZkJtQmt0dDUwbGptUWpmQW5lV21tZzF5VTRlSWZvR3AvamgrWW9TUGkyTzZTQi9ZVVJpZnNFYmlUK1RoMQpGdmpZTWhCb1VmQ2NGaGlIb3hDWXJOREhNOURSM21lUVI5ZkFuTEhKNEdXclhoMy84TjFhTngwcnZXckdSNDlJCkJrenNJdjErL2hHNzdyVG54Z3VPNGx0QVZ0QnljdVhRa2ZoWlpzMCtNSXphMzZpaVJja1lVRVVzYVFtQkJnUXMKaHdJREFRQUIKLS0tLS1FTkQgUFVCTElDIEtFWS0tLS0tCg==</data>
	<key>public-key-size</key>
	<integer>2048</integer>
	<key>signature-by</key>
	<string>void-package-github-actions</string>
</dict>
</plist>
```

</details>
<p align="center">
  <a>
	  <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
  </a>		  
</p>

<p align="center">
	<a href="https://github.com/Kennel-Linux/nwg/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&logo=gitbook&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
