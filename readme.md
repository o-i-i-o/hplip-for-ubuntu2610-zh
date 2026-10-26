```bash
sudo apt install libjpeg-dev   libsnmp-dev libavahi-client-dev libcups2-dev    libusb-dev libusb-1.0-0-dev  python3-setuptool   python3-dev libsane-dev libavahi-core-dev
```
```bash
  ./configure --with-hpppddir=/usr/share/ppd/HP --libdir=/usr/lib64 --prefix=/usr --enable-network-build --enable-scan-build --enable-fax-build --enable-dbus-build --disable-qt4 --enable-qt5 --disable-class-driver --enable-doc-build --disable-policykit --disable-libusb01_build --disable-udev_sysfs_rules --enable-hpcups-install --disable-hpijs-install --disable-foomatic-ppd-install --disable-foomatic-drv-install --disable-cups-ppd-install --enable-cups-drv-install --enable-apparmor_build --enable-hplip_testing_flag  
  ```

```bash
  make
 sudo make install
 sudo usermod -a -G lp $USER
```

and reboot your system