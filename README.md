# Ring -3 bootkit  
  
# Setup Windows  
- Disable Hyper-V => open CMD as admin and type: bcdedit /set hypervisorlaunchtype off  
- Spoofer requires TPM ENABLED!
- Launch info.exe and message me the string copied to clipboard for whitelist  
- Loader will automatically disable all of Windows Telemetry and security features upon reboot  
  
# USB Setup  
- Format USB drive as FAT32  
- Download decryptor from Telegram channel  
- Decrypt "bootx64.efi.X"  
- Create folder called EFI, create another folder called Boot and place the decrypted "bootx64.efi" inside second folder  
- Reboot system  
- Register cheat with the serial key [If you're a new user]  
- Sign in  
- Load cheat  
- You can now remove the usb flash drive, it is no longer required. The Bootkit is "written" to the Motherboard  
=> The cheat will automatically update the bootkit for upcoming Intel security patches and Windows updates, no user action required  
=> To unload and uninstall the cheat, sign in to the website and press the corresponding buttons and reboot  
  
# Setup UEFI  
- Disable Secure Boot  
- Delete Secure Boot Keys  
- Boot Order: UEFI USB priority then boot drive  
- Disable Fast Startup  
- Enable TPM  

