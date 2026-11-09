# Ubuntu Package Management

**Status: Planned**

Ubuntu uses APT to manage many software packages.

Commands to learn:
```bash
sudo apt update
apt list --installed
apt search <package-name>
sudo apt install <package-name>
sudo apt remove <package-name>
```

`apt update` refreshes package metadata; it does not itself upgrade installed packages. Practise installing and removing a small, familiar package in the VM.
