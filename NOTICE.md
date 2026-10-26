# NOTICE

This repository is a fork of OpenCode, the open source coding agent.

- Upstream: https://github.com/anomalyco/opencode (formerly `sst/opencode`)
- Upstream license: MIT (see `LICENSE`)
- Fork maintainer: `topixyoussef-lab`
- Fork created: 2026-10-27

## License

The upstream code is licensed under the MIT License. The original `LICENSE`
file is kept unmodified: the copyright notice and permission notice must stay
in every copy and in any distributed build.

Modifications made in this fork are released under the same MIT License.

## Changes in this fork

None yet. Every user-visible change lands as its own commit and is listed here.

## Plugins

Plugins are not part of this fork's core. They load from `.opencode/plugins/`
or `~/.config/opencode/plugins/`, or as npm packages declared in the config.
Treat third-party plugins as untrusted code: they run inside the agent process
and can read environment variables and credentials.
