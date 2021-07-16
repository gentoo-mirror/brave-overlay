If you are reading this on github, this means you are on a mirror.    
Please submit issues to https://gitlab.com/jason.oliveira/brave-overlay

### How to add this repo in eselect:

    sudo eselect repository enable brave-overlay    
    sudo emerge --sync brave-overlay    
    sudo emerge www-client/brave-bin::brave-overlay    

### How to add this repo in Layman:

    sudo layman -a brave-overlay    
    sudo layman -s brave-overlay
    sudo emerge www-client/brave-bin::brave-overlay
