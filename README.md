# myrpi

> Transform your Raspberry Pi into a powerful development machine in minutes.

One command. Zero hassle. Everything you need to start coding on your Raspberry Pi.

## What is myrpi?

**myrpi** is an automated setup script that transforms a fresh Raspberry Pi into a fully-configured development environment. It installs modern developer tools, configures your shell with helpful aliases and functions, and sets up git workflows - all automatically.

## Why myrpi?

✨ **Save Hours of Setup Time** - What takes hours to install manually happens in minutes
🔒 **Reliable & Safe** - SHA256 verification ensures you get legitimate software
🔄 **Idempotent** - Run it multiple times safely; it won't break existing configurations
⚡ **Modern Tools** - Get the latest development tools: neovim, fzf, ripgrep, lazygit, and more
🎨 **Enhanced Shell** - Beautiful prompts, smart aliases, and powerful completions out of the box
🔧 **Extensible** - Easy to add your own tools and configurations

## Quick Start

```bash
# Clone the repository
git clone https://github.com/wfairclough/myrpi.git
cd myrpi

# Run the setup (requires sudo)
sudo ./init.sh setup

# Reload your shell
source ~/.bashrc
```

That's it! Your Raspberry Pi is now ready for development.

## What Gets Installed?

- **Modern text editor** (neovim with LazyVim)
- **Version managers** (asdf for Node.js, uv for Python)
- **Enhanced CLI tools** (bat, eza, fzf, ripgrep, zoxide, atuin)
- **Git workflow tools** (lazygit, GitHub CLI, custom aliases)
- **Development utilities** (jq, yq, httpie, tmux, htop)

Plus automatic configuration of your shell with:
- Smart command aliases
- Git shortcuts
- Custom functions for common tasks
- Beautiful, informative prompt
- Enhanced shell history

## Requirements

- Raspberry Pi 4 Model B (ARM64)
- Raspberry Pi OS (Debian-based)
- Internet connection
- `sudo` privileges

## Learn More

For detailed documentation on extending the script or troubleshooting.

## License

MIT License
