**Test Setup: 512 GB DRIVE (GPT-UEFI)**

**Boot into the arch install media and run the following commands.**

iwctl device list (not required for ethernet)

iwctl station *device* scan

iwctl station *device* get-networks

iwctl --passphrase *password* station *device* connect *SSID*

pacman -Sy --noconfirm git

git clone https://github.com/customlinux/arch

/bin/bash arch/install/base

**Login by entering your username and password.**

ls

./name_of_desktop_environment

**Enjoy.**
