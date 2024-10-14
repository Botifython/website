Botifython is a modern Python framework designed for SEO and AI integration,
leveraging Nix Flakes for a reproducible, robust development environment.
It focuses on automation, seamless setup, and scalable features. Built to handle
the complexity of SEO tools while integrating advanced AI capabilities, this project
ensures consistent environments across platforms, using automated updates and
SSH keys to keep everything up-to-date with minimal manual intervention.

The first step is getting Nix installed on your system.

# Installing Nix on macOS or Windows

This guide provides straightforward instructions for installing Nix on macOS or Windows using the Determinate Systems installer.

## Installation Steps

1. Open your terminal (Terminal on macOS, or WSL2 terminal on Windows).

2. Run the following command:

   ```bash
   curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install
   ```

3. Follow any on-screen prompts to complete the installation.

## What This Does

- Sets up Nix on your system (macOS, Linux, or Windows via WSL2)
- Enables Nix flakes and the unified CLI by default
- Stores an installation receipt at `/nix/receipt.json` for easier uninstallation
- Places a copy of the install binary at `/nix/nix-installer`

