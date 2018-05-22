# How_to_build_DL_BOX


Download Ubuntu16.04 iso (link)

Install ISO on your own USB (link) 

BIOS setup
`F2` to access the BIOS,

advanced mode, Disable Fast Boot In BIOS  

boot bootdevice  uefi and
boot from storage UEFI only 

boot key management , mount usb
save secure boot key 

delete PK
make sure secure boot state disabled


exit and save 


F2
choose the boot UEFI your usb


choose install ubuntu
# install Ubuntu
[if you meet black screen problem(in Chinese, update it later)](ubuntu_black_screen(Chinese).md)

## check your driver and download it
[for Titan Xp] http://www.nvidia.com/download/driverResults.aspx/128737/en-us

[grub-efi-amd64-signed failed to install into /target/ error](https://forums.linuxmint.com/viewtopic.php?f=42&t=122276)

```bash
sudo bash filename.run
```

## before you install Nvidia Driver
[stop X sever](stop_X_service.md)


# optional:
[How to mount the hard drive in computer directory as data folder](mount_harddrive_as_data.md)

[How to enable ssh service](http://ubuntuhandbook.org/index.php/2016/04/enable-ssh-ubuntu-16-04-lts/)

[set up permission to each user](link)

[ubuntu system ](http://www.rodsbooks.com/linux-uefi/#preparing)
