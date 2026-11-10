# Cotilleo Convo for Pi

A planned standalone Pi plugin for agent delegation, conversations and collaboration.

**Pre-development: not implemented.** This repository contains documentation only. There is no installable plugin, published release or verified compatibility matrix.

[Contribute](CONTRIBUTING.md) · [Issues](https://github.com/Yivas/cotilleo-convo-pi/issues) · [Security](SECURITY.md)

## Planned capabilities

The goal is to let a coordinator work alongside child agents and independent peers, with direct, group, team and global conversations. Users should be able to choose a coordinator or specialist as their conversation partner without transferring authority or resource ownership.

An authorized session view is planned for current and historical conversations, including sessions that have not been contacted. Unknown coverage must remain visible. Channel-specific context should avoid waking every agent or sending every conversation to every model.

Delivery, acceptance, execution and verification will need separate states. Messages must not grant permissions, cooperative reservations must not be presented as isolation, and recovery must not blindly repeat uncertain mutations. These are design requirements, not available features or security guarantees.

## Scope and status

The Pi plugin is intended to work independently of the OpenCode plugin. Host APIs, model and MCP configuration reuse, delegation-policy compatibility, terminal interaction and shutdown behavior still require research and testing. No supported host versions or installation commands are offered yet.

There is no sandbox, remote-control service or application in this repository. A future interface must distinguish hiding a conversation from explicitly stopping owned work and must not terminate independent sessions.

## Participation and license

This is a collaborative open-source project maintained by Yivas. Documentation corrections, proposals, issues and pull requests are accepted through [CONTRIBUTING](CONTRIBUTING.md). Acceptance of a contribution does not imply a delivery date. Security reports use the private channel in [SECURITY](SECURITY.md), not public issues.

Copyright (c) 2026 Yivas. Licensed under the [MIT License](LICENSE).
