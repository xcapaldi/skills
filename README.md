# Agent Skills

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)

A curated collection of my personal agent skills that are safe to expose.

## Structure

This entire repo operates as a Claude Code plugin [marketplace](https://code.claude.com/docs/en/plugin-marketplaces).
All skills try to conform to the [Agent Skills](https://agentskills.io/home) specification along with the extended Claude support. They should work with Claude, Claude Cowork and Claude Code (CLI and UI) but everything is still being tested.

## Usage

### Vercel's skills.sh

```
npx skills@latest add xcapaldi/skills
```

### Claude Code CLI

If you're using Claude Code in the CLI, you can install this marketplace directly with:

```
/plugin marketplace add xcapaldi/skills
```

You can then manage the markeplace and the installation of its constituant plugins via the CLI as a normal marketplace.

### Claude/Claude Cowork/Claude Code UI

Claude Cowork and Claude Code UI support plugins but only from Anthropic partners.
Claude only supports direct skills.
This means that for all three, you'll need to install individual skills manually.
Skills are just zipped with the `.skill` suffix and then installed in the **Customize** menu.
