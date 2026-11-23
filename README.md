🍅BLOOM ZONES Manager

A Bash-based management utility for Ubuntu servers.

📌 About

BloomZones Manager is a server administration project designed to simplify selected management tasks through a command-line menu.

✨ Features

- Bash-based installation
- Command-line management menu
- SSH configuration validation
- SSH configuration backup before applying changes
- Automatic downloading of project files from GitHub

🖥️ Requirements

- Ubuntu Linux server
- Root privileges
- Internet connection
- "curl" or "wget"
- OpenSSH server

📥 Installation

Run the following command on your Ubuntu server:

bash <(curl -fsSL https://raw.githubusercontent.com/Andreapeter769-lgtm/manager/main/install.sh)

Alternatively, download the installer first:

curl -fsSL https://raw.githubusercontent.com/Andreapeter769-lgtm/manager/main/install.sh -o install.sh

Review the script before running it.

📂 Repository Files

- "install.sh" — Main installation script
- "menu.sh" — Command-line management menu
- "ssh" — SSH configuration template

⚠️ Important Notes

- Review all scripts before executing them as root.
- Back up your server configuration before making changes.
- Confirm SSH access settings before applying the SSH configuration.
- Keep your server and installed packages updated.

👨‍💻 Author

Andreapeter769-lgtm

GitHub: https://github.com/Andreapeter769-lgtm/manager

📄 License

Add a license file if you intend to distribute this project. Do not assume that the project is open-source licensed until a license is selected.
