# Project_RIS

Mobile Robot 개발 Project


KERNEL=="ttyUSB[0-9]*", ATTRS{idVendor}=="10c4", ATTRS{idProduct}=="ea60", ATTRS{serial}=="0011", SYMLINK+="ttyIMU", GROUP="ris", MODE="0666"
KERNEL=="ttyUSB[0-9]*", ATTRS{idVendor}=="10c4", ATTRS{idProduct}=="ea60", ATTRS{serial}=="0010", SYMLINK+="ttyRPLidar", GROUP="ris", MODE="0666"
KERNEL=="ttyUSB[0-9]*", ATTRS{idVendor}=="0403", ATTRS{idProduct}=="6001", ATTRS{serial}=="A10LT0DR", SYMLINK+="ttyRS485", GROUP="ris", MODE="0666"

USB Symbolic Links
