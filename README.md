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

## Software specific:

### To deal with externally-managed python error
```
sudo rm /usr/lib/python3.*/EXTERNALLY-MANAGED
```
