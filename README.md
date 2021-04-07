### How to add this repo in eselect:

sudo eselect repository enable brave-overlay    
sudo emerge --sync brave-overlay    
sudo emerge www-client/brave-bin::brave-overlay    

### How to add this repo in Layman:

sudo layman -a brave-overlay    
Or    
sudo layman -o https://gitlab.com/jason.oliveira/brave-overlay/raw/master/repositories.xml -f -a brave-overlay
