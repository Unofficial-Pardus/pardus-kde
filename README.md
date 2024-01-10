Pardus 23 Backports KDE Unofficial

ISO yapmak için:

```
sudo apt update
sudo apt install curl mtools squashfs-tools grub-pc-bin grub-efi xorriso debootstrap -y
sudo bash build.sh
```

Kurulum sonrası:

```
sudo apt update
sudo apt upgrade
sudo update-grub
```

Günceleme: 10/01/2024
