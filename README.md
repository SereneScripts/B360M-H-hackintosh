# My Hackintosh build
Specs + changelog + EFI folder (if you need an example or want to use it with similar hardware)

I moved to a different motherboard now, and I will create new repository for it. This repo won't be updated anymore.

## Hardware
- Board: Gigabyte B360M H
- CPU: Intel Core i5-8400
- RAM: 2x16 GB DDR4-2666 XMP (Corsair Vengeance)
- Storage: Samsung 960 Evo 500 GB NVMe
- GPU: AMD Radeon RX 560 4 GB (MSI ITX AERO)
- Wireless: Broadcom BCM94360CD (Fenvi T919) 

## Software
- OpenCore 0.6.5
- macOS Big Sur 11.1

## Installation
Went smooth af, followed the usual [guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Performance
- Subjective: as fast as it could ever get
- Geekbench 5: [1004/5118](https://browser.geekbench.com/v5/cpu/5450060)
- Geekbench 5 Compute: [22225](https://browser.geekbench.com/v5/compute/2179427)
- Blackmagic Disk Speed Test: 1800 write/2500 read
- Cinebench R23: 1017 single-core/5674 multi-core

## What works 
Almost everything, including Unlock with Apple Watch, 4K/60/10 bit DisplayPort output, analog audio, sleep/wake, Wi-Fi and Bluetooth, AirDrop, Continuity, FileVault etc.

## What doesn't / to-do list
- [ ] Pick the right audio layout (11?)
- [ ] Fix hardware DRM & wireless Sidecar

## Quirks (and features :D)
Motherboard has latest UEFI firmware, F15b
CFG Lock option is present in UEFI, so no patching was required

## Backstory of this build
I had an iMac 5K (Late 2015) in top-of-the-line-but-not-custom configuration: i5-6600, 16 GB DDR3-1866, Radeon R9 M395 2 GB, 2TB Fusion Drive (128 GB flash & 2 TB HDD).

It ran slower than I expected and had some annoying problems. To fix the machine, I had to disassemble it, replace noisy cooling system, replace hard drive, replace flash storage, and add more memory. Or just sell it and get a newer one (Apple's way of fixing things™).

Above-mentioned upgrades are expensive. New Apple 256 GB Gen. 5B SSDs have insane prices, and 4x8 or 2x16 SO-DIMM sticks of DDR3-1866 are impossible to source these days. Plus, I had to pay for disassembly and reassembly of this computer (or risk breaking the display). 

So I've sold it... and built a Hackintosh instead! I was aiming at 2x performance for 0.5x of second-hand market price of this iMac, and I think it's there. Excited! 

## Acknowledgments
* Apple for macOS
* Apple for making insanely expensive but cool Intel machines that are almost impossible to upgrade or repair (or afford, for that matter)
* Dorthania for the guides
* Hackintosh community for everything