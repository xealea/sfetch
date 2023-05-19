## Example Output Of SimpleFETCH

<a href="https://imgbb.com/"><img src="https://i.ibb.co/pKgSXPG/Screenshot-2023-05-19-20-31-25-1366x768.png" alt="Screenshot-2023-05-19-20-31-25-1366x768" border="0" /></a>

**The logo glyph displayed next to the window manager text will change based on the Linux distribution being used.**

For example the script is like this
```bash
# Define icons based on distribution
if [ -f "/etc/arch-release" ]; then
    distro_icon=""
elif [ -f "/etc/debian_version" ]; then
    distro_icon=""
elif [ -f "/etc/gentoo-release" ]; then
    distro_icon=""
elif [ -f "/etc/zorin-release" ]; then
    distro_icon=""
elif [ -f "/etc/deepin-version" ]; then
    distro_icon=""
elif [ -f "/etc/elementary_version" ]; then
    distro_icon=""
elif [ -f "/etc/devuan_version" ]; then
    distro_icon=""
elif [ -f "/etc/alpine-release" ]; then
    distro_icon=""
elif [ -f "/etc/almalinux-release" ]; then
    distro_icon=""
elif [ -f "/etc/endeavouros-release" ]; then
    distro_icon=""
else
    distro_icon=""
fi
```
Feel free to add your favorite Linux distribution by becoming a contributor and submitting a pull request.

# SimpleFETCH (sfetch)
SimpleFETCH (sfetch) is a lightweight system information tool inspired by Neofetch. It displays basic system information in the terminal.

## Installation
Download the sfetch script and place it in the /usr/bin/ directory (requires sudo access):
```bash
sudo wget -O /usr/bin/sfetch https://github.com/xealea/sfetch/raw/master/sfetch
```
Make the scripts executable
```bash
sudo chmod +x /usr/bin/sfetch
```

## Usage
To use SimpleFETCH, open a terminal and run the following command:
```bash
sfetch
```
This will display the system information in the terminal.

## Customization
You can customize the output of SimpleFETCH by modifying the script. Open the `sfetch` script in a text editor and make changes according to your preferences.

## Dependencies
SimpleFETCH does not have any external dependencies and should work on most Unix-like systems.

## License
SimpleFETCH is released under the MIT License. See the [LICENSE](LICENSE) file for more information.
