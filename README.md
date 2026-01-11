# OpenCode CLI

Windows executable mirror of [OpenCode](https://github.com/anomalyco/opencode), automatically repackaged and released as standalone binaries.

This repository exists because [bin](https://github.com/marcosnils/bin) - an effortless binary manager for Windows - can only manage `.exe` files directly. We extract the executables from OpenCode's release archives and publish them here so you can install and manage them with `bin`.

## Installation

First, install `bin` if you haven't already. Head over to the [installation instructions](https://github.com/marcosnils/bin#-installation).

Then install the OpenCode binary:

```bash
bin install https://github.com/verzly/opencode-cli
```

When prompted, select the appropriate executable for your system.

## Usage

Once installed, you can use OpenCode directly from your command line. To update to the latest version:

```bash
bin update
```

To list all installed binaries:

```bash
bin list
```

## Important

Make sure the directory where `bin` installs itself is included in your `$PATH` environment variable. This is typically done during the `bin` installation process, but you may need to verify it manually.

## About

This is an automated mirror that extracts Windows executables from the [original OpenCode project](https://github.com/anomalyco/opencode) and publishes them as releases. New versions are checked and released automatically.