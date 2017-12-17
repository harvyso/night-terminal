![Night Terminal](https://i.imgur.com/XFIPiAD.png)

> A monochrome, minimalistic terminal that goes well with Night UI and Night Syntax.

## Screenshot

![Night Terminal Screenshot](https://i.imgur.com/dwuI268.png)

## Install
`apm install night-terminal`

## Usage
You can toggle the terminal open/close by pressing <kbd>Ctrl</kbd>+<kbd>\`</kbd>.
`night-terminal` stays in the bottom of your editor while you work.

## Commands
| Command | Action | Default Keybind |
|---------|--------|:-----------------:|
| night-terminal:new | Create a new terminal instance. | `ctrl-shift-t`<br>or<br>`cmd-shift-t` |
| night-terminal:toggle | Toggle the last active terminal instance.<br>**Note:** This will create a new terminal if it needs to. | `` ctrl-` ``<br>(Control + Backtick) |
| night-terminal:prev | Switch to the terminal left of the last active terminal. | `ctrl-shift-j`<br>or<br>`cmd-shift-j` |
| night-terminal:next | Switch to the terminal right of the last active terminal. | `ctrl-shift-k`<br>or<br>`cmd-shift-k` |
| night-terminal:insert-selected-text | Run the selected text as a command in the active terminal. | `ctrl-enter` |
| night-terminal:insert-text | Bring up an input box for using IME and special keys. | –––––––––––– |
| night-terminal:fullscreen | Toggle fullscreen for active terminal. | –––––––––––– |
| night-terminal:close | Close the active terminal. | `ctrl-shift-x`<br>or<br>`cmd-shift-x` |
| night-terminal:close-all | Close all terminals. | –––––––––––– |
| night-terminal:rename | Rename the active terminal. | –––––––––––– |

## Related Projects
- [Night UI](https://github.com/saadq/night-ui)
- [Night Syntax](https://github.com/saadq/night-syntax)
- [Hyper Night](https://github.com/saadq/hyper-night)

## License
MIT
