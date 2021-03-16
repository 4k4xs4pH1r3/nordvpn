*** Don't use root


# nordvpn installation

    sh <(curl -sSf https://downloads.nordcdn.com/apps/linux/install.sh)
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
