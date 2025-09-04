<div align="center">
  <img height="80" alt="icon" src="https://github.com/vague-theme/vague/blob/main/assets/icon.png?raw=true" />
  <h1>Vague for Wezterm</h1>
  <img alt="preview" src="https://github.com/user-attachments/assets/5589f855-fec1-4aea-a833-53b13caf690a" />
</div>

## Usage

1. Save [vague.lua](vague.lua) file in `~/.config/wezterm/lua/` directory.

2. In your `wezterm.lua` config, load the theme:
   ```lua
   local theme = require("lua/vague")
   ```

3. Add to your config table:
   ```lua
   return {
     colors = theme.colors(),
     window_frame = theme.window_frame(), -- optional, only if using fancy tab bar
   }
   ```

## Thanks to contributors

- [lukeburton00](https://github.com/lukeburton00)
- [skewb1k](https://github.com/skewb1k)
