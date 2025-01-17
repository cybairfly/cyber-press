# Display
xrandr --output eDP-1 --off
xrandr --output eDP-1 --auto

# Drivers
????
chrome://settings
nvidia-smi
OptimusUI
intel_gpu_top
vainfo
????

https://github.com/lilydjwg/dpms-off

# Fans
watch nbfc status
sudo nbfc config -a "Asus Zenbook Pro UX550VD"
sudo nbfc start

https://github.com/hirschmann/nbfc
https://github.com/cybairfly/nbfc-linux
https://github.com/nbfc-linux/nbfc-linux
https://github.com/hirschmann/nbfc/wiki/How-to-create-a-NBFC-config

# Disk
sudo mkdir /mnt/DATA
sudo guestmount -r -o allow_other -a /media/codey/OS/DATA.vhd -m /dev/sda2 /mnt/DATA