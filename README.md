# WozterDev downloads

Download the latest Windows installer from the [Releases page](https://github.com/WozterDev/wozterdev-downloads/releases/latest).

## Install

1. Download `WozterDevSetup.msi` from the latest release.
2. Double-click the MSI and follow the installer progress.
3. When setup reports that installation succeeded, click **Finish** and open WozterDev from the Start menu.

WozterDev installs for the current Windows account under `%LOCALAPPDATA%\Programs\WozterDev`. Projects, workspaces, environments, and locally installed service packages are stored under `%LOCALAPPDATA%\WozterDev` for that account. A different Windows account starts with its own settings and installed services.

WozterDev does not bundle database or web-server packages in the application installer. Install and enable those services from the Services page.

Project sites and enabled browser-based service URLs use the `.local` suffix.

## Installer verification

Each release includes `SHA256SUMS.txt`. Compare its hash with the downloaded MSI before installing. The MSI is currently unsigned, so Windows may display a publisher or reputation warning.
