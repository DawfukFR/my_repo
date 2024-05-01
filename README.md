# Archlinux Unofficial x86_64 Package Repository

This repository is dedicated to maintaining important packages that are not available on the Arch User Repository (AUR) for x86_64 architecture.

## How to Use

1. Add the following lines to your `/etc/pacman.conf` file:
 
[dawfukfr]
Server = https://dawfukfr.github.io/my_repo/x86_64

2. Import the repository key:
 
sudo pacman-key --keyserver keyserver.ubuntu.com -r 2B4541CB1E00B4FA0460F0BD6866ACE0590E73BB
sudo pacman-key --lsign-key 2B4541CB1E00B4FA0460F0BD6866ACE0590E73BB

3. Update your package list:
 
sudo pacman -Sy

4. Install packages from this repository using:
 
sudo pacman -S package_name

## Contributing

If you would like to contribute to this repository, feel free to submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
