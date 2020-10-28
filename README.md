# problem-ubuntu


# install Ubuntu Kubuntu ... on Asus X541U my problem in Realtek RTL8723BE PCIe Wireless Network Adapter

how to fix it :<br>

go into the BIOS and lock wireless and LAN <br>

install ubuntu kubuntu ....<br>

Edit /etc/default/grub. Change the line starting with GRUB_CMDLINE_LINUX_DEFAULT into <br>

GRUB_CMDLINE_LINUX_DEFAULT="quiet splash pci=noaer"<br>

Run sudo update-grub<br>

Reboot<br>
