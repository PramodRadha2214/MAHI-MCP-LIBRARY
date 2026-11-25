# MAHI MCP Library

A curated, security-conscious catalog of Model Context Protocol (MCP) servers and integrations for the MAHI AI / MAHI OS ecosystem.

## Purpose

This repository is the central index for discovering, evaluating, documenting, and integrating MCP servers into MAHI AI, OpenCode, desktop workflows, and automation systems.

## How to use this library

1. Browse [MCP-INDEX.md](MCP-INDEX.md) to find a tool by category.
2. Open the relevant category guide under `CATEGORIES/`.
3. Read the installation guide and compatibility notes before installing.
4. Review the security checklist in `SECURITY/SECURITY-CHECKLIST.md`.
5. Test new servers in an isolated environment before connecting them to personal data or production workflows.

## Repository structure

- `MCP-INDEX.md` — searchable master catalog
- `CATEGORIES/` — tools grouped by capability
- `INSTALLATION-GUIDES/` — installation and setup walkthroughs
- `CONFIGURATION-EXAMPLES/` — redacted configuration examples
- `SECURITY/` — security review policy and checklists
- `COMPATIBILITY/` — client and platform compatibility notes

## Curation policy

Each catalog entry should include the official source, purpose, supported transports, setup requirements, license, maintenance signals, security considerations, and last verification date. Entries are not endorsements and must be re-checked before installation.

## Security rules

- Never commit API keys, access tokens, passwords, private URLs, or personal data.
- Use environment variables or a local secret manager for credentials.
- Prefer official repositories and pinned releases/commits.
- Review dependencies, permissions, network access, and filesystem access.
- Avoid running unknown MCP servers with broad machine permissions.
- Do not mark a server as verified unless its source and setup have actually been checked.

## Adding an MCP server

Create a category entry using [MCP-ENTRY-TEMPLATE.md](CATEGORIES/MCP-ENTRY-TEMPLATE.md), then add a concise row to [MCP-INDEX.md](MCP-INDEX.md).

## Scope

This is a documentation and discovery library. Adding a server here does not automatically install or enable it on a device. Local integration should be performed deliberately in the target client after review.
