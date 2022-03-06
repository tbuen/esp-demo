# esp-demo
Spielwiese für ESP32
## esp-idf installieren
Benötigte Pakete für Arch Linux
```
pacman -S --needed gcc git make flex bison gperf python-pip cmake ninja ccache dfu-util libusb
```
Repository clonen
```
git clone -b v4.4 --recurse-submodules https://github.com/espressif/esp-idf.git esp-idf-v4.4
```
Tools installieren
```
./install.sh esp32
```
Die Tools werden in `~/.espressif` installiert, also bei einem Update des esp-idf ggfls. vorher das Verzeichnis löschen, um Platz zu sparen.

Um das esp-idf zu verwenden
```
. ./export.sh
