# macvendor

**macvendor** is a shell script to find MAC address vendors using the ieee-data OUI database.  
Supports multiple MAC formats, file input, stdin input, quiet mode, and localization.

## Installation (Debian)
sudo dpkg -i macvendor.deb

## Usage
macvendor -h
macvendor 00:11:22:33:44:55
macvendor -f macs.txt
echo "00-11-22-33-44-55" | macvendor
macvendor -q 00:11:22:33:44:55

## Localization
- Russian translation included (`locale/macvendor.po`)
- Compile `.mo` with `msgfmt macvendor.po -o macvendor.mo`

[![Buy Me a Coffee](https://img.buymeacoffee.com/button-api/?text=Buy+me+a+coffee&emoji=&slug=yourname&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff)](https://donatello.to/MichailKubrak?g=coffee)

[![Donate](https://img.shields.io/badge/Support%20Project-2ea44f?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://donatello.to/MichailKubrak?g=coffee)

[![Donate](https://img.shields.io/badge/☕%20Donate%20Me-FF813F?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://donatello.to/MichailKubrak?g=coffee)

