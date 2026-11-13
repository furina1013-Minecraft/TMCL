# TMCL — Tacitus MineCraft Launcher

TMCL is an independent Windows launcher for Minecraft: Java Edition.

- Microsoft OAuth 2.0 device-code login
- Users sign in with their own Microsoft accounts
- Xbox Live / XSTS / Minecraft Services authentication
- No password collection
- No account sharing or piracy features
- Not affiliated with Mojang Studios or Microsoft

## Authentication

TMCL uses the official Microsoft OAuth 2.0 device code flow. It requests only:

- `XboxLive.signin`
- `offline_access`

Access tokens are stored locally and encrypted with the Windows credential store
through Electron `safeStorage`. TMCL does not operate an authentication proxy
server and never receives the user's Microsoft password.

## Privacy

See [PRIVACY.md](PRIVACY.md).

## Contact

Email: your-real-contact@example.com
