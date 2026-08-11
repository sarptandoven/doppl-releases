# Personal Doppl privacy

## What stays on the Mac

Personal Doppl does not require a Doppl account. Its conversations, prompts,
repository and file access, agent execution, model credentials, memory,
artifacts, device key, and local database stay on user-controlled machines.
Doppl does not operate a server that receives this personal workspace data.

When a person shares a room, the invited device connects to the owner Mac over
the private HTTPS path the owner configured. The invited person can receive the
room's messages and invoke the agents exposed to that room. Other personal
work remains outside the grant. Tailscale has its own terms and privacy policy.

## Network requests

The Desktop application contacts GitHub's public release service to check for
and download signed updates when update checking is enabled. Claude Code,
Codex, Tailscale, model providers, editors, package registries, MCP servers, and
other tools a person chooses may make their own network requests under their
own terms.

Doppl product telemetry has no built-in Doppl-operated destination and is off
unless a person explicitly enables it and configures an endpoint. Personal
diagnostic reports are created only when the person chooses **Save diagnostic
report**. They remain local until that person opens and shares the file.

## Recovery and deletion

Portable backups are encrypted with the password chosen at export. They
include app-owned personal state and the device identity but not the contents
of an external working folder. Anyone holding both the backup and its password
can assume that restored device identity.

Removing the app does not silently erase personal data or an external working
folder. Destructive deletion must be a separate, explicit action. A person can
remove an invited computer under **Settings → Shared access** to revoke its room
access.
