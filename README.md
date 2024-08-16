My linux setup for keep record of all applications config.

It's the first aproach to manage dotfiles using GNU stow.

Installation:
  Clone the repositori in ~/ 
  Enter the folder cd ~/dotfiles 
  Execture stow . ( Install it in the case you have not installet jet )
  To clone the cinnamon config run: dconf load /org/cinnamon/ < connamon_config.dconf

Available configuration:
  Bash config .bashrc
  Text editor .selected-editor
  Cinnamon config keybindings-backup.dconf
  .config
    Autostart applications autostart
    rofi rofi
    Zed zed --> Nothing interesting
    Monitors config cinnamon-monitors.xml
    
  .local
    Custom scripts bin
    share
      Descktop files to icons applications
  

