# .BackNiriDank

Personal configuration for the [Niri](https://github.com/YaLTeR/niri) Wayland compositor.

## Project Structure
This configuration uses a modular approach, splitting various settings into specific files within the `dms/` directory. The main `config.kdl` imports these components to keep the configuration organized and maintainable.

### Included Modules
- `dms/colors.kdl`
- `dms/layout.kdl`
- `dms/alttab.kdl`
- `dms/binds.kdl`
- `dms/outputs.kdl`
- `dms/cursor.kdl`
- `dms/windowrules.kdl`

## Credits
This project utilizes the modular structure and configuration management approach inspired by **Dank Material Shell (DMS)**. Special thanks to the Dank Material Shell project for the framework and design principles that enable this modular setup.

## Installation
Ensure you have Niri installed. Copy the contents of this repository to your `~/.config/niri/` directory.

```bash
cp -r . /home/yourusername/.config/niri/
```
