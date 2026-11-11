# XPlay — Modular Game Launcher for Linux

**XPlay** (formerly AstraX Play) is an independent, modular game launcher for Linux developed by **AsyGames**. Its Qt Quick interface brings supported games into one customizable desktop experience.

🌐 **[Public project overview](https://github.com/asygames/xplay-launcher)** · 📦 **[Public releases](https://github.com/asygames/xplay-releases/releases)**

## About XPlay

XPlay organizes supported games in an animated, orbital launcher interface. Individual game integrations are modular, allowing the launcher and game modules to evolve separately.

Current integrations include:

- **Minecraft: Java Edition** — profile and instance management, Microsoft account sign-in, game downloads and launching. Supports Vanilla, Fabric, Quilt, Forge and NeoForge configurations.
- **Genshin Impact** — launch integration on Linux using an appropriate compatibility environment.
- **Roblox** — dedicated game-launcher module.
- **Counter-Strike 2** — launcher integration.
- **AstraX RGB** — lighting controls and integration.

XPlay is designed for Linux desktops and is distributed as an **AppImage** in its public release repository.

## Microsoft account and Minecraft integration

For Minecraft: Java Edition, XPlay supports the **Microsoft device-code authorization flow**. Users initiate sign-in through XPlay, then complete authentication on Microsoft's own website. **XPlay does not ask users to type their Microsoft password into the launcher.**

The Minecraft module uses authorized Microsoft/Xbox Live/Minecraft services to identify the signed-in account, validate access to Minecraft where required, retrieve the player's profile and launch the game. Microsoft authorization is not intended to bypass any license, ownership, authentication or service requirements.

Authorization data is handled locally by XPlay; the current implementation stores Microsoft refresh tokens in a locally encrypted vault. See our [Privacy information](PRIVACY.md) for details.

**We are seeking approval of the XPlay application registration to support this legitimate authentication integration.**

## Availability

Download published builds from **[XPlay Releases](https://github.com/asygames/xplay-releases/releases)**. Supported runtime requirements and version-specific release details are documented there.

The application's source code is maintained in a separate private repository. **This public repository is for product information and Microsoft/Minecraft authentication review, not for source-code distribution.**

## Publisher

**AsyGames** · [GitHub organization](https://github.com/asygames)

## Disclaimer

XPlay is an independent third-party application. It is **not affiliated with, endorsed by, or sponsored by Microsoft, Mojang Studios, HoYoverse, Roblox Corporation, or Valve**. Trademarks and game names belong to their respective owners.
