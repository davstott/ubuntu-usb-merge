ubuntu-usb-merge
================

Automating merging the read-write filesystem on Ubuntu USB back into the read-only part with a quick bash script. 

The process is described in my blog post here http://davstott.me.uk/index.php/2013/09/05/ubuntu-13-04-on-a-usb-flash-drive-and-merging-its-persistent-storage/ and whilst this process and script works for me, there are very few safety checks in it, so running this script as root might very well delete all of your data and run over the neighbours cat.  

Please be extra careful and take backups before you start. 

At the moment, it requires that mksquashfs be installed, which can be done with 
sudo apt-get install squashfs-tools
