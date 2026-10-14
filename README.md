# Electron by Nerc

**An independent Minecraft: Java Edition launcher for Windows.**

Electron by Nerc is a personal desktop software project focused on creating a customized Minecraft launching experience with mod management, game profiles, and a distinctive industrial sci-fi interface inspired by Minecraft voxel art.

> Project status: In development. Minecraft Services application approval is pending.

## About the Project

Electron by Nerc is being developed as a Windows desktop launcher for Minecraft: Java Edition.

The project aims to provide a unified interface for managing game installations, browsing compatible modifications, creating game profiles, and launching Minecraft.

The launcher features a custom interface inspired by the VOVA INDUSTRIES Minecraft world, combining industrial design, voxel-art environments, and science-fiction elements.

## Current Features

- Custom Electron desktop interface.
- Minecraft game profile management.
- Mod discovery through Modrinth.
- Mod installation with file integrity verification when available.
- Support for Vanilla and Fabric profiles.
- Game configuration and Java-related settings.
- Local settings and profile management.
- Discord Rich Presence integration, subject to configuration and testing.
- A custom Minecraft-inspired visual design.

Feature availability may vary by version. Some integrations remain under development or require additional configuration.

## Microsoft Authentication

The launcher is designed to use Microsoft's official authentication flow for Minecraft: Java Edition.

The intended flow is:

1. Microsoft account authentication.
2. Xbox Live authentication.
3. XSTS authentication.
4. Minecraft Services authentication.
5. Minecraft profile and game ownership verification.
6. Launching a compatible Minecraft installation.

The application is intended for users who own Minecraft: Java Edition.

**Minecraft Services application approval has not yet been confirmed.** Microsoft authentication and Minecraft authentication must not be considered fully operational until the complete flow has been successfully tested.

The project does not intend to bypass Microsoft authentication or Minecraft ownership verification.

## Privacy and Security

The project aims to:

- Use official authentication mechanisms.
- Keep authentication tokens out of the renderer and source repository.
- Avoid publishing passwords, access tokens, refresh tokens, or private credentials.
- Limit access to local files to the functionality required by the launcher.
- Use official mod distribution platforms where possible.

See [PRIVACY.md](PRIVACY.md) for additional information about data handling.

## Screenshots

Screenshots of the current application are available in [`docs/screenshots/`](docs/screenshots/).

They represent the development build and do not imply that every planned integration has been verified.

## Technology

- Electron
- Node.js
- HTML, CSS, and JavaScript
- Minecraft game-launching and profile-management libraries
- Modrinth API
- Microsoft OAuth and Minecraft Services integration under development

## Project Status

This is an independently developed personal project. Features are added and tested incrementally.

Microsoft authentication, Minecraft Services approval, and external integrations may require additional configuration or validation.

## Disclaimer

Electron by Nerc is an independent project and is not affiliated with, endorsed by, or sponsored by Microsoft, Mojang Studios, or Xbox.

Minecraft is a trademark of Microsoft Corporation.

## Contact

For questions or project-related issues, use the GitHub Issues section of this repository.

Repository owner: Nerc

