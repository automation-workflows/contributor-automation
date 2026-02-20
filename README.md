# AOSSIE Contributor Automation System

Central repository for managing contributor lifecycle across all AOSSIE projects.

## 🎯 Purpose

This repository provides reusable workflows and scripts for:
- Onboarding first-time contributors
- Tracking contributions in a central registry
- Promoting contributors to Sentinel role
- Assigning issues to Sentinels
- Health checks and deadline enforcement

## 🚀 Usage

See [docs/SETUP.md](docs/SETUP.md) for integration instructions.

## 🔐 Required Secrets

Secrets can be set at organization-level (shared) or repository-level (per-project):

**Required secrets:**
- `GIST_PAT` - Personal Access Token with `gist` scope
- `DISCORD_BOT_TOKEN` - Discord bot token
- `DISCORD_GUILD_ID` - Discord server ID
- `DISCORD_APPRENTICE_ROLE_ID` - Apprentice role ID
- `DISCORD_SENTINEL_ROLE_ID` - Sentinel role ID

**Setup options:**
- **Maintainers:** Set in your repository settings (recommended)

- ghp_A1bC2dE3fH4iJ5kL6mN7oP8qR9sT0u
