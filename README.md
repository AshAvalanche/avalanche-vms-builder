# Avalanche VMs builder

[![Sync and build releases of Avalanche VMs forks](https://github.com/AshAvalanche/avalanche-vms-builder/actions/workflows/sync-avalanche-vms.yml/badge.svg)](https://github.com/AshAvalanche/avalanche-vms-builder/actions/workflows/sync-avalanche-vms.yml)

This repository contains GitHub Actions workflows to automatically build new versions of Avalanche VMs and attach the resulting binaries as assets to VMs' repositories.

## Target repositories

| VM          | Repository                                                                       | Latest version |
| ----------- | -------------------------------------------------------------------------------- | -------------- |
| blobvm      | [AshAvalanche/blobvm](https://github.com/AshAvalanche/blobvm/releases)           | `v0.0.9`       |
| spacesvm    | [AshAvalanche/spacesvm](https://github.com/AshAvalanche/spacesvm/releases)       | `v0.0.9`       |
| subnetevm   | [AshAvalanche/subnet-evm](https://github.com/AshAvalanche/subnet-evm/releases)   | `v0.4.0`       |
| timestampvm | [AshAvalanche/timestampvm](https://github.com/AshAvalanche/timestampvm/releases) | `v1.2.6`       |

## Scheduling

Daily around 00:00 UTC
