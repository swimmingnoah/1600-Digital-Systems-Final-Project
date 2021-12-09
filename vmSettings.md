# VM Settings 
![Vm Settings](/Assets/Screen%20Shot%202021-12-08%20at%207.38.50%20PM.png)
### Here are the changes we are going to make to correctly setup your Ubuntu VM

    Name: Ubuntu
    Description: Optional
    CPU Mode: Host Passthrough ({Your CPU})
    Logical CPUs: {Choose CPU Threads}

    Initial Memory: {}
    Machine: Q35-5.1
    BIOS: OVMF
    USB Controller: 2.0 (EHCI)
    OS Install ISO: {Path to OS Install ISO}

    Primary vDisk Location: Auto
    Primary vDisk Bus: SATA
    
    Unraid Share: N/a
    Unraid Mount tag: N/a

    Graphics Card: VNC
    VNC Video Driver: QXL (best)
    VNC Password: {Optional}
    VNC Keyboard: English-United States

    Sound Card: None

    Network MAC: {Pre Filled}
    Network Bridge: {Br0}
    Network Model: {virtio}

    USB Devices: N/a
    Other PCI Devices: N/a
---

### You now can press create and you will now have a fully functional Ubuntu VM

## You can Go [Home Here](README.md)