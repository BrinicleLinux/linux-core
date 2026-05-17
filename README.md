# Brinicle Linux

<<<<<<< HEAD
Minimal Debian-based Linux distribution for servers and development environments.
=======
Minimal Debian(12)-based Linux distribution for servers and development environments.
>>>>>>> 33a0d97 (few changes)

## Features

- Debian 12 (Bookworm) base
<<<<<<< HEAD
=======
- Command-line only, no GUI
>>>>>>> 33a0d97 (few changes)
- Pre-installed: openssh-server, curl, wget, git, vim, nano, htop, neofetch
- Small ISO size (~450 MB)

## Download

Check [Releases](https://github.com/holcc1145-byte/brinicle-linux/releases)

<<<<<<< HEAD
=======
## Login

| Account | Password |
|---------|----------|
| brinicle | brinicle |
| root | root |

>>>>>>> 33a0d97 (few changes)
## Build

```bash
git clone https://github.com/holcc1145-byte/brinicle-linux.git
cd brinicle-linux
sudo apt install live-build
sudo lb config --distribution bookworm
sudo lb build
