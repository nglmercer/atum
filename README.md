# Atum

Atum is a Fabric mod for Minecraft 1.16.1 designed to automate the process of resetting for speedruns. It allows for both random seed and set seed resets with a single keypress.

## Features

- **Auto-Reset:** Quickly reset your world without navigating through multiple menus.
- **Random and Set Seeds:** Support for both random seed and set seed resets.
- **SpeedrunAPI Integration:** Easily configurable through the SpeedrunAPI menu.
- **Safety Hotkey:** Prevents accidental resets when typing in chat or other text fields.
- **Illegal Settings Warning:** Warns you if your world settings are not compliant with standard speedrunning rules.
- **Custom Seed Providers:** API for other mods to provide seeds to Atum.

## Installation

1. Install the [Fabric Loader](https://fabricmc.net/use/).
2. Download the latest version of Atum and place it in your `mods` folder.
3. Download the [SpeedrunAPI](https://github.com/contariaa/SpeedrunAPI) and place it in your `mods` folder.

## Usage

- The default hotkey to reset is **F6**. This can be changed in the standard Minecraft controls menu.
- Configuration can be accessed through the SpeedrunAPI config menu (usually found in the options menu).

## Building from Source

To build Atum from source, you will need Java 17.

1. Clone the repository:
   ```bash
   git clone https://github.com/contariaa/atum.git
   ```
2. Navigate to the directory and run the build command:
   ```bash
   ./gradlew build
   ```
3. The built JAR file will be located in `build/libs/`.

## License

Atum is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
