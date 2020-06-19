*** Don't use root


# nordvpn installation

    wget https://repo.nordvpn.com/deb/nordvpn/debian/pool/main/nordvpn-release_1.0.0_all.deb && sudo gdebi nordvpn-release_1.0.0_all.deb && sudo apt-get update -y && sudo apt-get install nordvpn && sudo apt-get autoclean && sudo apt install -f && sudo apt install neofetch -y && sudo apt -f install && sudo apt autoremove -y && apt-get clean cache && sudo apt update && sudo apt-get autoclean && apt-get clean cache && sudo apt update && sudo apt update -y && sudo apt full-upgrade -y --allow-downgrades && sudo dpkg --configure -a && sudo grub-mkconfig && cd && neofetch
#

#
# nordvpn sign in

    nordvpn login

#
# nordvpn activate ninja mode

    nordvpn c United_States && nordvpn s cybersec on && nordvpn s autoconnect on United_States && nordvpn s killswitch on && nordvpn s notify off && nordvpn settings && nordvpn status
#    
# nordvpn deactivate ninja mode

    nordvpn s killswitch off && nordvpn d && nordvpn s cybersec off && nordvpn s autoconnect off && nordvpn s notify off && nordvpn settings && nordvpn status
    
#
# nordvpn Close Session

    nordvpn logout
