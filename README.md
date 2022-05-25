<h1><img src="https://raw.githubusercontent.com/jeremehancock/repo.ubuntuce.com/main/logo.png" height="50" /> UbuntuCE DEV Repo</h1>

This is the DEV repo for [UbuntuCE](https://ubuntuce.com/).

**DO NOT USE!**

**THIS IS ONLY USED DURING THE DEVELOPOMENT OF UBUNTUCE!**

## Usage

#### Add UbuntuCE Repo Key
`wget https://dev.ubuntuce.com/KEY.gpg && gpg --output ubuntuce-dev.gpg --dearmor KEY.gpg && sudo mv ubuntuce-dev.gpg /usr/share/keyrings/ && rm KEY.gpg`

#### Add UbuntuCE Repo
`sudo apt install curl -y && sudo curl -s --compressed -o /etc/apt/sources.list.d/ubuntuce-dev-jammy.list "https://dev.ubuntuce.com/ubuntuce-dev-jammy.list"`

#### Update Packages
`sudo apt update`

## Disclaimer

All code is provided as-is without any warranty.
