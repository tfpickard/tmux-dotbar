<div align="center">

<h1> Tmux dotbar </h1>

Tmux dotbar is status bar theme for tmux <br>

<br>


[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

</div> 

## Preview
<p align="center">
<div align="center">

![preview](./preview.png) 

</div>
</p>

## Installation
### TPM (Recommended)
1.  Install [TPM](https://github.com/tmux-plugins/tpm)
2.  Add the plugin:

    ```bash
    set -g @plugin 'vaaleyard/tmux-dotbar'
    ```
3. Inside tmux, use the tpm install command: `prefix + I` (default prefix is ctrl+b)

### Manual
1. Clone this repository to your desired location (e.g. `~/.config/tmux/plugins/tmux-dotbar`).

   ```bash
   mkdir -p ~/.config/tmux/plugins/
   git clone https://github.com/vaaleyard/tmux-dotbar.git
   ```
2. Add the following line to your `tmux.conf` file:
   `run ~/.config/tmux/plugins/tmux-dotbar/dotbar.tmux`.
3. Reload Tmux by either restarting or reloading with `tmux source ~/.tmux.conf`.


