sıfır vdi oluşturmak için

öneri freebsd 13.0

env PAGER=cat freebsd-update fetch

freebsd-update install

reboot

pkg update -f

pkg install gdb gcc8 gcc9 gcc10 gcc11 dep gmake cmake openssl python subversion unzip devil
