# Ansible Playbook - Lalmat's Favorite App Desktop

This playbook install my prefered desktop apps available under Ubuntu.

## Stuff
- [Joplin](https://joplinapp.org/) - Wonderfull note app with encryption & sync
- [Spotify](https://www.spotify.com/) - Music Player
- [BitWarden](https://bitwarden.com/) - Maybe the best Password Vault
- [VLC](https://www.videolan.org/index.fr.html) - Video Player
- [OBS Studio](https://obsproject.com/fr/download) - Video Capture & Streaming platform
- [Flameshot](https://flameshot.org/) - Not the best, but a working & flexible screenshot tool
- [Brasero](https://doc.ubuntu-fr.org/brasero) - Simple CD/DVD Burner
- [Cura](https://ultimaker.com/fr/software/ultimaker-cura) - A 3D printer slicer
## Requirements

You need to have theses packages already installed (use apt to install them) :
- git
- ansible
- software-properties-common

## Installation

Just run this command :

`sudo ansible-pull -U https://github.com/lalmat/ansible-ubuntu-apps.git`

Done.