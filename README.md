# ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA

# My hardware components:

 - Asus Tuf Gaming Z790-Plus Wifi D4 Bios 1611
 - Intel Raptor Lake i7-13700K 3.42Ghz – 5.40Ghz
 - MSI Radeon RX 6600 XT MECH 2x 8G
 - WD_Black SN850X M.2  1TB Nvme
 - Kingston KC3000 M.2  2TB Nvme
 - G.Skill Ripjaws 64GB 4 Slots DDR4 3200Mhz CL16 
 - Corsair RM1000 – 1000 Watt 80 Plus Gold PSU
 - Noctua NH-U14S CPU Cooling
 - Fenvi T919 PCI-E Wifi & Bluetooth 

# -------------------------------------------------------
- This study contains OpenCore folder in the EFI System Partition of SSD  and some advices
- OpenCore 0.9.9 is the current version
- Recomended SmBios is iMacPro 1.1 
- You must create your own serial number from the Platforminfo/DataHub-Generic-PlatformNVRAM section in OpenCore Configurator
- If you are using a network card like Fenvi T919, you must apply Post-install Root using OpenCore-Legacy-Patcher in order for it to work on Sonoma. You can download the app from this link : https://github.com/dortania/OpenCore-Legacy-Patcher/releases

# -------------------------------------------------------
# Bios Settings
- Ai Tweaker → Ai Overclock Tuner → Choose XMP profile
- Advanced → CPU Configuration → Active Performance Cores = All
- Advanced → CPU Configuration → Active Efficient Cores = All
- Advanced → CPU Configuration → Hyper-Threading = Enabled
- Advanced → System Agent (SA) Configuration → VT-d = Enabled
- Advanced → System Agent (SA) Configuration → Graphics Configuration → IGPU Multi-Monitor = Disabled
- Advanced → Thunderbolt(TM) Configuration → Discrete Thunderbolt Support = Disabled
- Advanced → PCI Subsystem Settings → Above 4G Decoding = Enabled
- Advanced → PCI Subsystem Settings → Re-Size BAR Support = Disabled
- Advanced → USB Configuration → XHCI Hand-off = Enabled
- Advanced → Onboard Devices Configuration → USB power delivery in Soft Off state (S5) = Enabled
- Advanced → Onboard Devices Configuration → Connectivity mode (Wi-Fi & Bluetooth) = Disabled or ( Enable for using onboard Wifi and Bluetooth )
- Advanced → Onboard Devices Configuration → Serial Port Configuration → Serial Port = Disabled
- Boot → CSM (Compatibility Support Module) → Launch CSM = Disabled
- Boot → Secure Boot → OS Type = Windows UEFI mode (or Other OS)
- Boot → Secure Boot → Secure Boot Mode = Custom
- Boot → Secure Boot → Key Management → Clear Secure Boot Keys
- Boot → Boot Configuration → Fast Boot = Disabled

# -------------------------------------------------------
# What's working
- All original Mac features work except Sidecar
# ------------------------------------------------------
![Ekran Resmi 2024-04-13 17 38 27](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/1409a3de-fc65-4209-96ae-1909f28d1c84)
![Ekran Resmi 2024-04-13 17 40 55](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/0ec1eac1-29e6-43ca-a064-ac27114a769e)
![Ekran Resmi 2024-04-13 18 01 12](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/bd43d498-90ec-42ed-8657-ed311123f7c0)
![Ekran Resmi 2024-04-13 16 50 37](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/a742e971-86f2-4ca0-b278-3f47505bdd98)
![Ekran Resmi 2024-04-13 16 50 42](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/ab81e370-b003-468c-9a32-e17159fbbdad)
![Ekran Resmi 2024-04-13 16 50 46](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/bb8c778e-9605-414f-8d67-64a0f1f46416)
![Ekran Resmi 2024-04-13 17 32 25](https://github.com/taranta/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-SONOMA/assets/28186049/9f8c22dd-0071-436d-bf04-c575673809b6)


# ----------------------------------------------------

# Thanks to:
- <a href="https://www.olarila.com">Mald0n</a> - For DSDT Patch and awesome tutorials
- <a href="https://github.com/dortania/OpenCore-Legacy-Patcher">dortania</a> - OCLP,SSDT and  other awesome hackintosh works
- <a href="https://github.com/acidanthera">Acidanthera</a> - OpenCore Boot Loader, AppleALC, Lilu & WhateverGreen, VirtualSMC
- <a href="https://www.tonymacx86.com/threads/asus-tuf-gaming-z690-plus-wifi-d4-alder-lake-i7-12700k-amd-radeon-rx580.323247/">frontgear</a> - For inspiration




