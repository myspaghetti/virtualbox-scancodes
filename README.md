# virtualbox-scancodes

Ever wanted to send a whole bunch of key-presses (like... a shell script!) to a guest virtual machine from the host, but the guest had no obvious way of communicating with the outside world? VBoxManage keyboardputscancode is the answer! And now instead of typing all those scancodes manually, you can use a script to translate ASCII strings into scancodes!
