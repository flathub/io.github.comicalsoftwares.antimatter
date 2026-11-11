<div align=center>

<img width="241" height="241" alt="AppIcon" src="https://github.com/user-attachments/assets/aecbdeb4-5fc7-4f77-b4b1-908c5e0626d0" />

# Antimatter
A modern, lightweight and absurdly optimized Python IDE written in **Python and PyQT6**
This is the flathub version of [the OG project](https://github.com/ComicalSoftwares/Antimatter/)
</div>

> [!WARNING]
> Antimatter's current development status is in **beta**. While totally usable as a daily driver, we do not recommend you to uninstall your current IDE yet as it is still a W.I.P (Work in Progress)

> [!NOTE]
> The warning above applies more to the OG Project more than the flathub release. This flatpak version is very usable and pretty stable.

## What is this repository about exactly ?
This flathub repository explicitly holds the manifest for building, updating and installing the flathub version of this project.

### How to install ?
You basically run this simple command which will download the latest stable release:
```bash
flatpak install flathub io.github.comicalsoftwares.antimatter
```
### How to build the manifest locally ?
Clone the repository first !
```bash
git clone https://github.com/flathub/io.github.comicalsoftwares.antimatter.git
```
Then make sure you have `flatpak-builder` installed. If not, then install it please.
```bash
flatpak-builder --install --user --repo=repo build io.github.comicalsoftwares.antimatter.json --force-clean
```
(I have no clue if that's how it works lol)

## Useful links
Please use these links for the following tasks:
* **Checking out the main repository & Source Code:** [ComicalSoftwares/Antimatter](https://github.com/ComicalSoftwares/Antimatter)
* **Issues & Bug Reporting:** [ComicalSoftwares/Antimatter/issues](https://github.com/ComicalSoftwares/Antimatter/issues)
* **View official Flathub Listing:** [flathub.org/apps/io.github.comicalsoftwares.antimatter](https://flathub.org/apps/io.github.comicalsoftwares.antimatter)
