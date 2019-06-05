# resolv-dns
As no complete network display is native for Linux here is a simple script to give the same kind of complete display we remember using 'ipconfig -all' on Windows. 

It makes use of nmcli to do the hard work and Zenity to provide a display window. Nothing too complex here.

As a result the dependencies are Network Manager CLI - nmcli and Zenity both of which should be available from your distribution repositories. I have used this on both Gentoo and Arch flavours with KDE Plasma 5 desktop though it should also work for Gnome etc.

Install to resolv-dns to /usr/local/bin and it should work for you.
