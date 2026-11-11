# XPlay — Privacy & Authentication Information

**Last updated:** November 11, 2026

This page describes the Microsoft account authentication features of **XPlay**, an independent Linux game launcher maintained by **AsyGames**. The behavior described here concerns the current Minecraft Java Edition integration.

## Microsoft authentication

When a user chooses Microsoft sign-in, XPlay uses the Microsoft device-code authorization flow. Users complete authentication through a Microsoft-hosted page; **XPlay does not request or collect Microsoft account passwords**.

Once authorization is granted, the launcher uses the resulting authorization credentials as needed for Microsoft's identity services, Xbox Live authentication and Minecraft services, including account/profile verification and access to games the account is entitled to use.

## Local credential storage

The Minecraft module currently stores Microsoft refresh tokens locally in an AES-256-GCM encrypted vault under the user's game data directory. The encryption key is also stored on the user's device in a separate protected file. This helps prevent accidental disclosure but does **not** protect the tokens from someone with unrestricted access to the user's files.

Do not share authentication files, tokens, screenshots of token values, or diagnostic logs containing credentials.

## Third-party services

Signing in and launching games may contact Microsoft, Xbox Live, Minecraft/Mojang and other services used by the games installed or launched. Those services process data under their own privacy policies.

## Account control

Users can manage their Microsoft accounts in the launcher. Removing an account requires reauthorizing to use that account again. Users may also revoke XPlay authorization in their Microsoft account security/permissions settings.

## Scope and updates

This information is provided for application review and product transparency. The functionality and policies may be updated as XPlay evolves. This page is not a statement of affiliation with Microsoft or any game publisher.

## Contact

For questions about XPlay or its Microsoft authentication integration, contact the publisher through [AsyGames on GitHub](https://github.com/asygames).
