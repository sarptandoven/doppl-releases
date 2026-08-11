# Doppl releases

Official signed downloads for Doppl Desktop.

Doppl runs personal work on your computer. No account or login is required.
When you choose to collaborate, you can share an individual room through a
private one-use link without moving your conversations, repositories, agents,
credentials, or files to a Doppl-operated server.

## macOS pilot

- [Apple Silicon Mac](https://github.com/sarptandoven/doppl-releases/releases/latest/download/Doppl-0.2.0-rc.1-arm64.dmg)
- [Intel Mac](https://github.com/sarptandoven/doppl-releases/releases/latest/download/Doppl-0.2.0-rc.1-x64.dmg)
- [Release notes and verification files](https://github.com/sarptandoven/doppl-releases/releases/latest)

Both Mac builds are signed with Developer ID, notarized by Apple, stapled, and
accepted by Gatekeeper. Each release includes `SHA256SUMS` and a
machine-readable lifecycle certification report.

This is a controlled pilot release candidate. Back up important work before
evaluating update and recovery flows.

## Five-minute demo

1. Open the correct DMG, drag Doppl to Applications, and launch it from Finder.
2. Choose **On this Mac**, then **Open personal Doppl**. Pick the folder Doppl
   may work in. No account, password, server URL, Docker, Python, or terminal is
   required.
3. Start a personal conversation and run an agent. Personal work remains private
   and usable without creating a team or inviting anyone.
4. For a two-Mac demo, connect both Macs to the same Tailscale network. On the
   owner Mac, open **Settings → Shared access** and follow the private-sharing
   setup. Create a room and copy its one-use invitation.
5. Open the invitation on the second Mac. It receives access to that room only,
   not the owner's personal conversations, other rooms, files, credentials, or
   settings.
6. Exchange messages, then remove the second Mac under **Shared access**. Its
   access closes immediately and stays removed after both apps restart.
7. Create a password-encrypted recovery copy under **Settings → Backup &
   recovery** before testing updates or reinstalling the app.

## Pilot boundaries

- Private room sharing requires Tailscale on both Macs. Doppl does not operate a
  relay for room contents.
- The owner Mac must be awake and reachable for invited people to use its room.
- Each person runs agents from their own connected Mac and approves their own
  folder boundary.
- This release contains macOS builds only. Windows is not part of this pilot.
