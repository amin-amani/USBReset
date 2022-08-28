# USBReset
UBUNTU USB reset port utility 

### Get the Bus and Device ID of the USB device you want to reset:

```
lsusb  
Bus 002 Device 003: ID 0fe9:9010 DVICO  
Make our compiled program executable:
```
### Change permission
```
chmod +x USBReset
```
### Execute the program with sudo privilege; make necessary substitution for <Bus> and <Device> ids as found by running the lsusb command:

```
sudo ./USBReset /dev/bus/usb/002/003  
```
