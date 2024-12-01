Blender on Termux with Hangover Wine

Run Blender on Android using Termux and Hangover Wine. This repository provides a streamlined setup for installing Blender on Termux using the arm64 version of Hangover Wine, courtesy of the `tur` package.

What's Included

- A simple script to install and configure Hangover Wine and Blender
- Pre-configured wine settings for optimal performance
- arm64 version of Blender, compatible with Hangover Wine

Requirements

- Termux installed on your Android device
- `tur` package installed (provides Hangover Wine)
- arm64-compatible device

Usage

- Copy and paste the following command into Termux:
```
curl -o install https://raw.githubusercontent.com/gamextra4u/Blender-on-Termux/0.1/install && chmod +x install && ./install
```
- Once installed, simply type `blender` to launch Blender with inputbridge.

Notes

- This setup is exclusively for arm64 devices
- Performance may vary depending on your device's hardware and software configuration
- As Blender is native arm64, no emulation is required

Contributing

Feel free to contribute to this repository by reporting issues, suggesting improvements, or submitting pull requests!

Credits

- Hangover Wine: https://github.com/AndreRH/hangover
- Blender: https://www.blender.org/
- Termux: https://termux.com/
- Termux-x11: https://github.com/termux/termux-x11

License

This repository is licensed under the MIT License.
