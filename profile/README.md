[Decentralized Auth](https://decentralizedauth.net/index.html#decentralized-auth)
=================================================================================

![](https://decentralizedauth.net/decentralizedauth-512.webp)

[![Discord](https://img.shields.io/discord/997020034499100753.svg?color=%237289da&label=Discord&logo=discord&logoColor=%237289da)](https://discord.gg/3aymtSFwcP) [![Matrix](https://img.shields.io/badge/Matrix-bridged-brightgreen?logo=matrix)](https://matrix.to/#/#decentralized-auth:antonok.com) [![GitLab](https://img.shields.io/badge/GitLab-source-orange?logo=gitlab)](https://gitlab.com/decentralizedauth) [![Modrinth](https://img.shields.io/badge/Modrinth-download-green)](https://modrinth.com/mod/decentralizedauth)

Decentralized Auth is an alternative authentication system for Minecraft client or server implementations.

With Decentralized Auth, player identity is tied to a cryptographic keypair so that no Mojang or Microsoft API calls are ever required on either the client or server.

[Use cases](https://decentralizedauth.net/index.html#use-cases)
---------------------------------------------------------------

-   Exercise your power against chat signing and any future anti-features that Microsoft may release in connection with authentication services
-   Continue to use the official Minecraft client after an unfair account ban
-   Host a private server among friends without enforcing strict chat moderation policies
-   Implement custom composable whitelist-based authentication logic on your server's website (2FA, account recovery, etc.)
-   Prevent Microsoft from gathering data about the servers you join
-   No more restarting your client because your auth session has expired

[Features](https://decentralizedauth.net/index.html#features)
-------------------------------------------------------------

-   Cross-compatibility - users authenticated with Microsoft can play together on the same server as Decentralized Auth users simultaneously
-   Full profile data - Share your skin texture (including your own custom cape!) and profile name to other players without a third-party endpoint
-   It's not just offline mode - all packets are E2E encrypted and your account cannot be stolen by logging in with your name
