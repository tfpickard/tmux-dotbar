<div align="center">

<h1> Tmux dotbar </h1>

Tmux dotbar is a simple and minimalist status bar theme for tmux. <br>
The session name is changed when the prefix key is pressed. <br>

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

## Recommended tmux options
Since this theme does not show the index of the windows, it's recommended for users that doesn't use a lot of windows.  
A good option is to set index numbers to start at 1, as it's easier to know which index refers to each window.
As well to renumber the windows when some of them are closed.

```
set -g base-index 1
setw -g pane-base-index 1
set-option -g renumber-windows on
```

