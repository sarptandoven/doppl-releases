# Doppl releases

Official signed downloads for Personal Doppl.

The supported 0.2 Mac release requires **macOS 12 Monterey or newer**. Both
Apple Silicon and Intel Macs are supported; choose the installer that matches
the processor shown under **Apple menu → About This Mac**.

Doppl runs personal work on your Mac. No Doppl account or login is required.
Conversations, repositories, agents, credentials, and files remain on machines
controlled by the people using them. Private room sharing connects those
machines directly over private HTTPS; Doppl does not operate a relay for room
contents.

## Download

Open the [release list](https://github.com/sarptandoven/doppl-releases/releases)
and choose the newest release offered for your cohort:

- `arm64.dmg` for Apple Silicon Macs;
- `x64.dmg` for Intel Macs.

Supported Mac builds are signed with Developer ID, notarized by Apple, stapled,
and accepted by Gatekeeper. Each release includes `SHA256SUMS` and
machine-readable build/lifecycle evidence. A release marked **Pre-release** is
a controlled pilot, not the stable channel.

## Five-minute personal journey

1. Mount the correct DMG, drag Doppl to Applications, and launch it from Finder.
2. Choose **On this Mac**, then **Open personal Doppl**. Pick the folder Doppl
   may work in. No account, password, server URL, Docker, Python, or terminal is
   required.
3. Start personal work with a Claude Code or Codex login already on that Mac.
   Doppl does not provide or host the model credential.
4. To share one room, connect both Macs to the same Tailscale network. On the
   owner Mac, open **Settings → Shared access**, enable the private HTTPS path,
   and create a one-use invitation.
5. Open that invitation in Doppl Desktop on the second Mac. It grants that
   computer the invited room only—not the owner's private work, repositories,
   credentials, memory, or settings.
6. Create a password-encrypted recovery copy under **Settings → Backup &
   recovery** before evaluating an update or replacing a Mac.

## Important boundaries

- The owner Mac must be awake and reachable while invited people use its room.
- Each person runs agents on their own Mac and approves their own folder.
- Tailscale is the supported private sharing path for the macOS pilot.
- Windows and Linux downloads are unsupported unless their release notes say
  that their signing and physical lifecycle gates are complete.
- Back up important work before evaluating a prerelease.

For ordinary help, read [SUPPORT.md](SUPPORT.md). Report a security issue
privately as described in [SECURITY.md](SECURITY.md). The local-data boundary is
spelled out in [PRIVACY.md](PRIVACY.md).
