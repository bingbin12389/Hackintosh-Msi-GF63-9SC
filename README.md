# Hackintosh
Install mac os 10.14.x to msi GF63-9SC laptop
stable EFI with Opencore 0.6.3

# Prepare installing
- An USB with storage > 32GB
- Disk imange mac OS 10.14.3 dmg
- Use Disk Genius or other Disk Utilities to partition the USB in 2 part: EFI & mac OS install partition
- Copy EFI folder to the partition EFI on USB
- Launch UEFI(BIOS) to boot from USB
- Choose install Mac OS -> do the rest of install

# Patch kext & Post install
- read the Opencore POST install guide
https://dortania.github.io/OpenCore-Post-Install/

# Features current support and running
- UHD graphic 630 : patched
- Wifi : itlwm work fine
- HDMI : patched
- Battery: have waring sign need to replace
- Audio : patched

# What not working
- NVDIA GTX 1650 : disabled

