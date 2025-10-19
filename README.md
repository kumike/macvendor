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

