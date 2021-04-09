# Clean Install of OpenMediaVault with ZFS
Instructions to Install Openmediavault with ZFS + some tweaks

## Install OpenMediaVault 5 with ZFS [Part 1] [Link To Video](https://www.youtube.com/watch?v=BMjpDUPF8E0){:target="_blank" rel="noopener"}

### Making a clean install of OpenMediaVault 5 using the ISO from [Here](https://sourceforge.net/projects/openmediavault/files/)

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
~~~

Now go to the Openmediavault webgui and login.
Go to OMV-Extras in the menu to the left right under Plugins.

Here you have to enable the "Testing repo" and click save and then apply.

Now you should be able to find the zfs plugin in the Plugins menu
or you can go back to the console and type in this command:

~~~
apt install openmediavault-zfs

exit
~~~

## Install OpenMediaVault 5 with ZFS [Part 4] [Link To Video](https://www.youtube.com/watch?v=HI5tUHJ8p_M)

### Here I am just making some prefered settings and tweaks.
### I am also installing some extra plugins wich I usally use.
