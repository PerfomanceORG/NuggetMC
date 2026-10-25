# NuggetMC

**A Minecraft server core written in Rust.**

[![Language](https://img.shields.io/badge/language-Rust-orange?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Status: In development](https://img.shields.io/badge/status-in%20development-yellow.svg)](#project-status)

NuggetMC is an independent Minecraft server software project derived from [PumpkinMC](https://github.com/Pumpkin-MC/Pumpkin). This repository is dedicated to the **server core**: its implementation, architecture, compatibility, and performance.

NuggetMC is not a Minecraft server network, client, or preconfigured server pack.

## Project direction

The project is being developed around a few practical goals:

- **Measure performance.** Publish reproducible benchmarks instead of unverified player-count or TPS claims.
- **Preserve expected gameplay.** Track compatibility and document behavior that differs from Minecraft.
- **Build deliberately.** Keep architectural changes understandable, testable, and documented.
- **Make progress visible.** Record implemented features and known limitations as the project evolves.

These are development goals, not claims that the features are already complete.

## Project status

NuggetMC is in early development and is **not ready for production use**. There is no official stable release yet. Feature coverage, Minecraft-version support, and performance results will be documented after they have been verified.

Build and run instructions will be added once the source tree and build process are available and validated in this repository.

## Development priorities

1. Publish and maintain the NuggetMC source tree.
2. Establish a reproducible build and automated checks.
3. Document Minecraft-version compatibility and implemented gameplay systems.
4. Create repeatable performance benchmarks and publish their methodology and results.

## Upstream project

NuggetMC is derived from [PumpkinMC](https://github.com/Pumpkin-MC/Pumpkin). We acknowledge the PumpkinMC maintainers and contributors whose work made this project possible. NuggetMC is an independent project and is not affiliated with or endorsed by the PumpkinMC team.

## Contributing

Ideas, bug reports, and questions are welcome through [GitHub Issues](https://github.com/PerfomanceORG/NuggetMC/issues). Please include relevant details and steps to reproduce when reporting a problem.

Contribution and build instructions will be expanded as the project structure takes shape.

## License

NuggetMC is distributed under the [GNU General Public License v3.0](LICENSE). The project is based on PumpkinMC, which is also licensed under GPL-3.0. See the license and notices in the repository for the applicable terms.

Minecraft is a trademark of Microsoft Corporation. NuggetMC is an independent community project and is not affiliated with or endorsed by Microsoft or Mojang Studios.
