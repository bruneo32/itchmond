# Itchmond
Embed a Nintendo DS emulator easily for [itch.io](https://itch.io) homebrew **NDS ROM** games

## Features
- Mobile friendly
- Controller support
- GPU acceleration
- Configurable

# Usage
- Download this repo as **ZIP** https://github.com/bruneo32/itchmond/archive/refs/heads/main.zip

- Add your game to the **ZIP** *(preferible filename `game.nds`)*

- Update the `config.json` if needed
  ```json
  {
    "title": "MyGame", // Will not be displayed usually
    "rom": "game.nds", // The filename inside the ZIP to load
    "enableMicrophone": false, // If your game uses the microphone
    "background": "#222" // The color of the emulator background
  }
  ```


- Go to your [itch.io dashboard](https://itch.io/dashboard) and edit you game page
- Select **Kind of project**: ***HTML***

- Upload the **ZIP** you have prepared and set the following configuration
  ![image](https://i.imgur.com/08UHaDh.png)

- Also include the following image somewhere in your game's description to show the emulator controls
  ![image](https://i.imgur.com/a6Pb9yr.png)
  > Credits: https://rhosgfx.itch.io/vector-keyboard-controls, https://robthefivenine.itch.io/flat-gamepad-icons

- **Done!** Publish your game
