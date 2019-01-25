# MacInstallScript
for lab macs


!/bin/bash
echo install script

mkdir install_files

echo install homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

echo install Inkscape
brew install caskformula/caskformula/inkscape


curl -o ~/install_files/OpenSCAD.dmg https://files.openscad.org/OpenSCAD-2015.03-3.dmg

curl -o ~/install_files/Fusion360.dmg https://dl.appstreaming.autodesk.com/production/installers/Fusion%20360%20Client%20Downloader.dmg

curl -o ~/install_files/Chrome.dmg https://dl.google.com/chrome/mac/stable/GGRO/googlechrome.dmg

Curl -o ~/install_files/Arduino
