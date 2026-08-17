# Doppl support

Use the [public support tracker](https://github.com/sarptandoven/doppl-releases/issues)
for installation, startup, update, backup, restore, invitation, or revocation
problems that are not security vulnerabilities.

The supported 0.2 pilot runs on macOS 12 Monterey or newer, on Apple Silicon
or Intel. Windows and Linux packages remain diagnostic unless their release
notes explicitly say otherwise.

[Choose the template](https://github.com/sarptandoven/doppl-releases/issues/new/choose)
that matches your symptom—Doppl will not start, Doppl stopped responding, my
agent gave no reply, sharing or joining a room failed, update or restore
problem, or something else. Each one asks for exactly what we need; answering
its questions is usually the difference between one reply and five.

Before filing an issue:

1. Open **Settings**, find the **Personal Doppl → Need help?** panel, and
   choose **Save diagnostic report**. If you cannot find that panel, say so in
   the issue—we can still help without it.
2. Open the JSON yourself. It is designed to contain coded health state and
   coarse size/age bands—not conversations, prompts, repositories, folder
   paths, credentials, invitations, device identifiers, URLs, or raw logs.
3. Include the Doppl version, macOS version, Intel/Apple Silicon, the step that
   failed, what you expected, and the diagnostic JSON only if you choose to
   share it.

Never post invitation URLs, credentials, backup passwords, private keys,
conversation or agent output, prompts, customer content, repository files, or
folder paths. An issue here is public and permanent. Use the private process in
[SECURITY.md](SECURITY.md) for a suspected vulnerability.

Personal Doppl is local-first, so there is no central workspace operator who
can recover unbacked-up data. Keep a verified encrypted backup before updates
or device replacement. During a prerelease pilot, a signing, startup,
device-identity, room-access, update, repair, or restore failure pauses cohort
expansion until it is resolved.
