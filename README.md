# cursor config

inspired by https://earthly.dev/blog/vscode-git/

## where i belong

`settings.json` in `~/.config/Cursor/User/settings.json`
`keybindings.json` in `~/.config/Cursor/User/keybindings.json`

## setup

ensure cursor is not open

`git clone` this anywhere, eg. `~/.cursor_config`

symlink the `settings.json` and `keybindings.json` from `~/.config/Cursor/User`

eg
```bash
ln -s ~/.cursor_config/settings.json ~/.config/Cursor/User/settings.json
ln -s ~/.cursor_config/keybindings.json ~/.config/Cursor/User/keybindings.json
```

done

## TODO

see the feasibility of sharing the `settings.json` and `keybindings.json` with vscode

