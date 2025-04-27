# Kinda Nvim

> [!NOTE]
> The `kinda_nvim` and `kinda_nvim_light` themes have been merged into Helix and will be available in the next release (after **25.01**). See [PR #13406](https://github.com/helix-editor/helix/pull/13406) for details. To use the themes now, follow the installation instructions below.

A beautiful, dark and light colorscheme for Helix, inspired by the default Neovim colorscheme. Includes `kinda_nvim` (dark theme) and `kinda_nvim_light` (light theme), with enhanced support for LSP and Tree-sitter syntax highlighting.

**Features:**
- Elegant dark (`kinda_nvim`) and light (`kinda_nvim_light`) themes
- Optimized for Helix’s LSP and Tree-sitter integration
- Carefully crafted color palette for readability and aesthetics
- Seamless integration with Helix’s built-in features

## Screenshots

### Dark Theme `kinda_nvim`
<img width="800" alt="Dark Theme" src="https://github.com/user-attachments/assets/275bd258-8940-4d0f-a4d5-70736e7cc63d" />

### Light Theme `kinda_nvim_light`
<img width="800" alt="Light Theme" src="https://github.com/user-attachments/assets/eafff380-9da0-4d08-b9a2-2de2573aca19" />

## Installation

1. Download the theme files:
  - kinda_nvim.toml
  - kinda_nvim_light.toml
2. Place the downloaded files in your Helix themes directory:
```bash
mkdir -p ~/.config/helix/themes
mv <path/to>/kinda_nvim.toml ~/.config/helix/themes/kinda_nvim.toml
mv <path/to>/kinda_nvim_light.toml ~/.config/helix/themes/kinda_nvim_light.toml
```

Alternatively, you can clone the repository and copy the files:

```bash
git clone https://github.com/strash/kinda_nvim.hx.git
cp kinda_nvim.hx/kinda_nvim.toml ~/.config/helix/themes/kinda_nvim.toml
cp kinda_nvim.hx/kinda_nvim_light.toml ~/.config/helix/themes/kinda_nvim_light.toml
```

## Usage

To use the theme, add the following to your `config.toml` in `~/.config/helix/`:
```toml
theme = "kinda_nvim" # For the dark theme
# OR
theme = "kinda_nvim_light" # For the light theme
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

Distributed under the MIT License. See [LICENSE](https://github.com/strash/kinda_nvim.hx/blob/main/LICENSE) for more information.

