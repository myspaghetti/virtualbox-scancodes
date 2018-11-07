# virtualbox-scancodes

Send keys when the VirtualBox guest has no sensible way of communicating with the outside world like SSH, for example in the EFI shell or before the OS is installed.

# Usage

source scancodes.sh - loads functions from script  
sendkeys - sends a string of ASCII keys as typed  
sendspecial - sends special characters by name, space delimited  
sendenter - sends ENTER key  
printksc - print names of special key scancodes
