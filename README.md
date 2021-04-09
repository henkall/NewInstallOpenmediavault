# Clean Install of OpenMediaVault with ZFS
Instructions to Install Openmediavault with ZFS + some tweaks

## Install OpenMediaVault 5 with ZFS [Part 1] [Link To Video](https://www.youtube.com/watch?v=BMjpDUPF8E0)

### Making a clean install of OpenMediaVault 5

## Install OpenMediaVault 5 with ZFS [Part 2] [Link To Video](https://www.youtube.com/watch?v=Wn_IwMI4dcY)

### Installing OMV Extras and the Proxmox kernel

Commands used:

~~~
wget -O - https://github.com/OpenMediaVault-Plugin-Developers/packages/raw/master/install | bash

omv-installproxmox

reboot
~~~

## Install OpenMediaVault 5 with ZFS [Part 3] [Link To Video](https://www.youtube.com/watch?v=d0TyNZpYxRs)

### Removing unnecessary kernels and installing ZFS on Openmedaivault 5

Commands used:

~~~
omv-removekernels

omv-update

apt install openmediavault-zfs

exit
~~~

## Install OpenMediaVault 5 with ZFS [Part 4] [Link To Video](https://www.youtube.com/watch?v=HI5tUHJ8p_M)

### Making some prefered settings and tweaks.
### Also installing some extra plugins.
