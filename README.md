# Linux command I have used and liked.

## Firstly the common one:

### To send or pull a file from network location.
```
scp --deprecated but works pretty well still.
``` 
usage: scp [file origin] [username]@[address]:[destination]

### To find the WAN IP of current machine.
```
curl ifconfig.me
```

### To see disk usage
```
df -h
```
-h for human-readable format

### CLI system monitor
```
top
```

### To see Memory usage
```
free
```
* -m to display in MB
* -g to display in GB

### Network Adaptor manager --CLI w/ GUI
```
nmtui
```
## System Level

``ctl`` + ``alt`` + ``F1`` is a short cut to force into text console

the number in F1 or F2 is used to force into tty1 or tty2. Linux use tty1 as default for outputing kernal info.

## Software specific:

### To deal with externally-managed python error
```
sudo rm /usr/lib/python3.*/EXTERNALLY-MANAGED
```
