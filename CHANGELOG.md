# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

- chore(deps): Go 1.26.5 and nox SDK v1.17.0 (#15)
- chore(security): nox remediation (deps + actions) (#14)
- ci: add nox-remediate caller (deps + action-pin remediation)
- build(deps): bump sigstore/cosign-installer from 3.10.1 to 4.1.2 (#6)
- ci: point the registry notice at where entries actually go (#13)
- ci: add nox self-scan and changed-files PR gate (#12)


## [Unreleased]

## [0.2.0] - 2026-07-18

### Added

- Finding dedup, confidence and rule filtering, so a triage run sends less to the model

  Reconciles work that had accumulated only in nox's `plugins/` directory,
  where a duplicate copy of this plugin lived. That copy has now been removed;
  this repository is the single source.

## [0.1.0]

Earlier releases predate this file. See the
[releases page](https://github.com/Nox-HQ/nox-plugin-llm-triage/releases) for their notes.
