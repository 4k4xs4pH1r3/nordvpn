# nordvpn installation

    wget https://repo.nordvpn.com/deb/nordvpn/debian/pool/main/nordvpn-release_1.0.0_all.deb && sudo gdebi nordvpn-release_1.0.0_all.deb && sudo apt-get update -y && sudo apt-get install nordvpn && nordvpn login
#
#
#
# nordvpn activate ninja mode
    nordvpn s cybersec on && nordvpn s killswitch on && nordvpn s autoconnect on United_States && nordvpn c United_States && nordvpn status && nordvpn s notify off
    
# nordvpn deactivate ninja mode

    nordvpn s killswitch off && nordvpn d && nordvpn s cybersec off && nordvpn s autoconnect off && nordvpn status
