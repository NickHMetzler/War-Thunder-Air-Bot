# War Thunder Air RB Bot

![App Screenshot](assets/screenshots/main_screenshot.png?raw=true "Air Bot Main Screen")

   This is a Bot designed to play many planes in War Thunder automatically.

   The list of working planes are:
   - Kfir Canard (IS)
   - F-4F (GR)
   - MiG-23BN (GR)
   - Mirage 5F (FR)
   - F-84F (FR)

   The list of supported resolutions are:
   - 2560x1080 
   - 2560x1440

   It automatically plays the game and bombs bases to generate silver lions and research points. Please follow the instructions below to set up and use the bot effectively.

## Installation

   1. Download the latest release of the War Thunder Bot from the GitHub repository.
   2. Extract the downloaded files to a convenient location on your computer.

## Setup

   ### Setting in game Parameters
   1. Open Controls menu.
   2. Set `Mouse Wheel (aircraft)` to `Throttle axis`.
   3. Set `Fire countermeasures` to `M.Wheel Down`(Mouse Wheel Down).
   4. Set `Set Mission Bombing Target` to your preferred CCRP keybind.
   5. Set `Switch Radar/IRST search on/off` to your preferred Radar keybind.
   6. Set `Drop bomb series` to your preferred bombing keybind.
      
   ### Setting in game Visual Parameters
   1. Open Settings menu.
   2. In the `Battle Interface` tab, set all colors to default.
   3. In the`Air Battle Settings` tab, set HUD colors to default.

   ### Setting Program Keybinds
   1. Open the `data/keybinds.txt` file in a text editor.
   2. Review the default keybinds provided and modify them as needed to match your preferred settings in game.
   3. Set `Switch Radar/IRST search on/off` to your preferred Radar keybind.
   4. Save the `data/keybinds.txt` file.

   ### Setting Up Auto Activation Key
   1. Open the `.env` file in a text editor.
   2. After the = on the line with `activation_key` paste in your activation key.
   3. Save the `.env` file.

   ### Keybind equivalents keybinds.txt vs in game
   - Keybind `bomb` in game is `Drop bomb series`.
   - Keybind `ccrp` in game is `Set Mission Bombing Target`.
   - Keybind `radar` in game is `Switch Radar/IRST search on/off`.
     
## Usage

   1. Run the `exe` file as Administrator to avoid any errors.
   2. Follow the on-screen instructions to start the bot.
   - To stop the bot, press and hold the `q` key for a second.
  
## Important Notes

   **The Bot is intended for personal use only.** Do not use it for any malicious or unfair purposes.
   Ensure that you have the latest version of the game installed on your computer for optimal compatibility.

## Disclaimer

   The Bot is a third-party tool and is not officially affiliated with or endorsed by Gaijin Entertainment, the developer of War Thunder. The use of this bot is at your own risk, and the developers and contributors are not responsible for any consequences resulting from its usage.

## Contributions

   Contributions to the Bot are welcome! If you encounter any issues or have suggestions for enhancements, please submit them via the GitHub repository's issue tracker or contact me directly if you wish to be part of the team.
