# Chromarchy

Chromarchy is a Unity Editor extension that lets you colorize and better organize your Hierarchy window. It helps you bring structure and visual clarity to large scenes by adding colors, labels and separators to your GameObjects.

> Note: This README is a generic starting point. Update the feature list and usage instructions to match the actual behaviour of the tool.

## Features

- Colorize GameObjects directly in the Hierarchy window
- Add visual separators and headers to group related objects
- Improve readability of large and complex scenes
- Lightweight, Editor-only tool (no runtime overhead)

## Requirements

- Unity 2021.3 LTS or newer (project currently uses the Universal Render Pipeline)

## Installation

### Option 1: Copy into your project

1. Download or clone this repository.
2. Copy the `Assets/Nekuzaky` folder into your own project's `Assets` folder.

### Option 2: Unity Package Manager (Git URL)

1. Open `Window > Package Manager`.
2. Click `+` then `Add package from git URL...`.
3. Paste the repository URL.

## Usage

1. Open the Hierarchy window in the Unity Editor.
2. Right-click a GameObject (or use the Chromarchy menu) to assign a color or label.
3. Organize your scene with headers and separators as needed.

## Project structure

```
Assets/
  Nekuzaky/
    _/Codes/Editor/Hierarchy/   # Editor scripts for the Hierarchy tool
```

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

## License

This project is currently unlicensed. Add a LICENSE file to define usage terms.
