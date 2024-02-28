# Jupiter
Jupiter ACPI platform driver DKMS for Ubuntu.
[Original](https://gitlab.com/evlaV/linux-integration)

## Build
```bash
git clone https://github.com/firlin123/jupiter-ubuntu-dkms.git
cd jupiter-ubuntu-dkms
sudo apt update
sudo apt install build-essential dkms debhelper dh-sequence-dkms
dpkg-buildpackage -us -uc
```
