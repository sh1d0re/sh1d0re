echo "deb http://deb.debian.org/debian/ bookworm main contrib non-free-firmware" | sudo tee /etc/apt/sources.list


echo "deb http://archive.raspberrypi.org/debian/ bookworm main" | sudo tee /etc/apt/sources.list.d/raspi.list


echo "deb http://security.debian.org/debian-security bookworm-security main" | sudo tee -a /etc/apt/sources.list


echo "deb http://deb.debian.org/debian/ bookworm-updates main" | sudo tee -a /etc/apt/sources.list
