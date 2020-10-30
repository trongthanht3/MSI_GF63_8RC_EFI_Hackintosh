# MSI GF63 8RC EFI for Hackintosh  
EFI of GF63 8RC (8th gen), may not work with 9th gen Intel  
- CPU: i7 8750h Coffe Lake  
- RAM: 16GB SKHynix 2133MHZ  
- SSD: just dont use 981pm/970evo+  
- Wifi: Intel AR9462 (worked with itlwm and heliport, please disable SIP then install kext to L/E)  
- Bluetooth: Native
- Trackpad/Keyboard: worked with VooDooPS2, still need fix for I2C, please pull request to help me if you fixed  
- Keyboard: layout Japan, worked with VoodooPS2  
  
# Worked:  
- Wifi (bad performence but still work, noted in itlwm FAQ) 
- Bluetooth  
- Backlight  
- PS2 Trackpad  
- hiDPI but too big logo  
- Audio: AppleALC Layout 35 but don't have mic
# NOTE:  
- Get Resource at: https://github.com/acidanthera/OcBinaryData and paste to EFI for GUI  
  
# Need to fix:  
- I2C Trackpad  
- Keyboard won't work without VoodooPS2  
- Bluetooth  
- Kernel panic when shutdown/restart  
- Microphone with AppleALC  
  


