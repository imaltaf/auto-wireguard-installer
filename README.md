# WireGuard-Install

WireGuard installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS, and Fedora.

This script will let you set up your own VPN server in no more than a minute, even if you haven't used WireGuard before. It has been designed to be as unobtrusive and universal as possible.

## Installation

1. **Clone and Run the Script:**

    Open your terminal and clone the following repo and run the WireGuard installation script:

    ```sh
    git clone https://github.com/imaltaf/wireguard.git
    ```
    ```sh
    sudo ./wireguard-install.sh
    ```
2. **Follow the Assistant:**

    The script will guide you through the installation process. Follow the prompts to complete the setup.

## Post-Installation

- **Re-run the Script:**

    After the initial setup, you can re-run the script to manage users or uninstall WireGuard. Use the same command to run the script again:

    ```sh
    bash wireguard-install.sh
    ```
    ## or

    ```sh
    sudo ./wireguard-install.sh
    ```

    You can:
    - Add more users
    - Remove existing users
    - Completely uninstall WireGuard

## No Server? No Problem!

If you want to run your own VPN but don't have a server for that, consider using [Oracle Free Tier](https://www.oracle.com/cloud/free/).

---

