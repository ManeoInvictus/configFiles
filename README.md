# configFiles
A repository of my collection of config files and widgets for AwesomeWM and VIM editor.

# vim
The vim folder contains the .vimrc file; to be placed in the home directory.
My vim is configured to function like a Python IDE; plugins managed by Pathogen. All the necessary links
for the plugin are in the .vimrc file. The base file is the sample file by Martin Brochhaus presented at PyCon APAC
2012. I have further modified it for my needs.

# awesome
The awesome folder contains the config files for awesome window manager. Clone this folder in ~/.config/
rc.lua is the main configuration file which handles the layout, themes, widgets etc. It is a modified file of the 
default config file located in /etc/xdg/awesome

theme.lua handles the theme. It is a modified file of the default file located at /usr/share/awesome/themes/default

xrandr.lua is a file for separating Multiple Monitor functions as a separeted module (taken from awesome wiki)
