# Etherboot 5.4.4 Boot ROMs

Collection of Etherboot Boot ROMs for writing to EPROMs. This is using the older Etherboot 5.4.4 ROMs for support on older ISA and PCI Ethernet cards.  Newer versions of gPXE and iPXE are too large and have issues running on older NICs. The reason for posting these Boot ROMs is because it's difficult to find already compiled ROMs, compiling is difficult since it requires 32-bit libraries, and ROM-O-Matic has been down. 

The majority of these Boot ROMs will fit on a DIP-28 27C512 EPROM. Some cards like the 3COMs have a configuration program that must run in DOS or Windows to enable booting from the Boot ROM once installed. 

# Why install a Boot ROM on my NIC?

Having the ability the ability to PXE boot from a PXE server can be very handy like:
* Running utilities like Memtest and CPUID without a floppy drive.
* Installing an OS like Windows without a CD drive.
* Easy access for cloning drives with Clonezilla.
* Booting, with enough RAM, and running an entire OS like Linux over the network.
