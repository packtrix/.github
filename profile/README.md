<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/packtrix/packtrix/main/docs/assets/logo/packtrix-logo-dark.svg">
    <img alt="Packtrix" src="https://raw.githubusercontent.com/packtrix/packtrix/main/docs/assets/logo/packtrix-logo.svg" width="320">
  </picture>
</p>

<p align="center"><strong>Declarative offline APT and RPM repositories.</strong></p>

<p align="center">
  <a href="https://packtrix.github.io/">Website</a> ·
  <a href="https://packtrix.github.io/docs/">Documentation</a> ·
  <a href="https://github.com/packtrix/packtrix">Source</a> ·
  <a href="https://packtrix.github.io/docs/roadmap/">Roadmap</a>
</p>

List the packages your air-gapped Linux machines need. Packtrix resolves every dependency for every distro you run, then builds signed APT and RPM repositories you can carry across the air gap.

- **One manifest for APT and RPM.** Name the distros; Packtrix knows their official repositories and signing keys.
- **Every change is reviewable.** A lockfile records exactly what crosses the air gap, and updates ship as small delta bundles.
- **Plain output.** Standard APT and RPM repositories, served by any web server, with nothing to install on the machines.

> **Early development.** Packtrix validates manifests today. The first release, v0.1.0, resolves and mirrors APT repositories for Ubuntu and Debian. Follow the [milestones](https://github.com/packtrix/packtrix/milestones).

Feedback on the design, real-world package lists and air-gap constraints are the most useful contributions right now: [open an issue](https://github.com/packtrix/packtrix/issues/new) or read the [contributing guide](https://github.com/packtrix/packtrix/blob/main/CONTRIBUTING.md).
