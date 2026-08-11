# Doppl security

## Report privately

Use [GitHub private vulnerability reporting](https://github.com/sarptandoven/doppl-releases/security/advisories/new).
Do not open a public issue for a vulnerability, and never include a live
invitation, private key, credential, repository content, conversation, or
diagnostic report containing information you have not reviewed.

Include the Doppl version, macOS architecture, what an attacker can gain, and a
minimal reproduction if it is safe to share. We aim to acknowledge a report
within three business days. There is no bug bounty.

## Supported releases

The newest stable macOS release receives security fixes. An explicitly active
macOS prerelease is supported only for its named pilot cohort. Older builds,
and Windows/Linux packages described as diagnostic, do not receive a security
support promise.

## Personal sharing boundary

Personal Doppl gives a device access to one room only after a one-use link and a
signed device-key challenge. Removing that device revokes its sessions and room
membership. Someone admitted to a room is trusted to read and act inside that
room; do not share a room containing work they should not see.

The owner Mac is the room server. Use the supported Tailscale private-HTTPS
path, keep both Macs patched, and turn sharing off when it is no longer needed.
Doppl does not operate a customer-work relay or make the owner Mac highly
available.
