# debian
debian package repository

sudo apt update --print-uris
 * https://wiki.debian.org/DebianRepository/Format#A.22Release.22_files
 * https://gist.github.com/ikbelkirasan/57e60bbcaecd0bd5cf2cbf441e744159
 * https://askubuntu.com/a/860731
 * https://blog.packagecloud.io/how-to-gpg-sign-and-verify-deb-packages-and-apt-repositories/

```
sudo apt install reprepro
reprepro -V --section misc --component main includedeb all <path-to>/ublksrv_1.0_amd64.deb
reprepro -V --section kernel --component main includedeb all <path-to>/ublk-dkms_6.1.123_all.deb
```
