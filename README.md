# tmux-conf

## About
Personal tmux configurations.

* Tmux Cheat Sheet & Quick Reference: https://tmuxcheatsheet.com/

## Getting Started

### Prerequisites

- Tpm: https://github.com/tmux-plugins/tpm

### Installation

1. Clone tpm

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

2. Copy the `.tmux.conf` file to the home directory:

```bash
cp .tmux.conf ~/
```

3. Install required plugins:

- Open tmux:

```bash
tmux
```

- Press `Ctrl + I` to install all plugins.

4. Install `xclip` for clipboard integration (if not already installed):

```bash
sudo apt install xclip
```

5. Ensure the virtual machine is configured to share the clipboard with the host system (if applicable).

## Contributing

To make a contribution, follow the steps below:

1. Fork the Project
2. Create a feature branch (`git checkout -b feature/newFeature`)
3. Commit changes
4. Push to the branch (`git push origin feature/newFeature`)
5. Open a pull request
