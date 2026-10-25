# NuggetMC

**A Minecraft server core written in Rust.**

[![Rust](https://img.shields.io/badge/language-Rust-orange?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-in%20development-yellow.svg)](#project-status)

NuggetMC is an independent server-core project based on [PumpkinMC](https://github.com/Pumpkin-MC/Pumpkin). This repository is focused on the software itself: its implementation, architecture, Minecraft compatibility, and measured performance.

NuggetMC is server software. It is not a Minecraft server network, client, or preconfigured server pack.

## Project direction

- **Measure, then report.** Performance claims should be backed by repeatable benchmarks and a clear test setup.
- **Track compatibility.** Document supported Minecraft versions, implemented behavior, and known differences.
- **Develop deliberately.** Keep changes reviewable and record the reasoning behind project-specific decisions.
- **Publish progress clearly.** Distinguish implemented features from ideas and future work.

These are project goals, not claims that the work is complete.

## Project status

The source tree is published, but NuggetMC remains in early development and is **not ready for production use**. There is no stable release yet. Compatibility coverage and performance results will be published after they have been verified.

Build and run instructions will be added after the workflow has been checked against this repository.

## Current codebase

The initial source snapshot is based on [PumpkinMC commit 224f9f8](https://github.com/Pumpkin-MC/Pumpkin/commit/224f9f8). Project-specific changes are developed in this repository and should be documented as they are introduced.

## Development priorities

1. Maintain a reproducible source build.
2. Establish automated checks for changes.
3. Publish a Minecraft-version compatibility matrix.
4. Create repeatable performance benchmarks and report their methodology and results.

## Upstream project

NuggetMC builds on the work of the [PumpkinMC maintainers and contributors](https://github.com/Pumpkin-MC/Pumpkin). NuggetMC is an independent project and is not affiliated with or endorsed by the PumpkinMC team.

## Contributing

Use [GitHub Issues](https://github.com/PerfomanceORG/NuggetMC/issues) to report bugs, ask questions, or suggest improvements. Include the Minecraft version, relevant logs, and steps to reproduce when applicable.

Project-specific contribution instructions will be published as the development workflow is established.

## License and notices

The server code is distributed under the [GNU General Public License v3.0](LICENSE). Some components and bundled data may carry separate license or attribution notices; retain and review those notices when redistributing them.

Minecraft is a trademark of Microsoft Corporation. NuggetMC is an independent community project and is not affiliated with or endorsed by Microsoft or Mojang Studios.
