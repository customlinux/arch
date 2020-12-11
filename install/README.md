**Test Setup: 512 GB DRIVE (GPT-UEFI)**

**Boot into the arch install media and run the following commands.**

- iwctl device list

- iwctl station *device* get-networks

- iwctl --passphrase *password* station *device* connect *SSID*

pacman -Sy --noconfirm git

git clone https://github.com/customlinux/arch

/bin/bash arch/install/base

**Login by entering your username and password.**

ls

./name_of_desktop_environment

**Enjoy.**
