# Fail2Ban Configuration

This directory contains configuration templates, scripts, and documentation to help you set up and configure Fail2Ban for your environment.

## Contents

- **[/config/](./config/)**
  - `jail.local.template`: A template for Fail2Ban jail settings.
  - `fail2ban.conf.template`: A template for the main Fail2Ban configuration file.
- **[/scripts/](./scripts/)**
  - `install-fail2ban.sh`: Script to install Fail2Ban on a Debian-based system.
  - `apply-fail2ban-configs.sh`: Script to apply the configurations and restart Fail2Ban.
- **[/docs/](./docs/)**
  - `fail2ban.md`: Documentation on configuring and customizing Fail2Ban.

## Usage

1. **Install Fail2Ban**:
   Run the [installation script](./scripts/install-fail2ban.sh) to install Fail2Ban on your system.

   ```bash
   bash scripts/install-fail2ban.sh
   ```

2. **Apply Fail2Ban Configurations**:
    Run the [apply configurations script](./scripts/apply-fail2ban-configs.sh) to apply the configurations and restart Fail2Ban.

    ```bash
    bash scripts/apply-fail2ban-configs.sh
    ```

3. **Customization**:
   Refer to the documentation in [/docs/fail2ban.md](./docs/fail2ban.md) for more information on customizing Fail2Ban.
