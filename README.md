# Bootkit  
 
 
# Setup Windows  
- Disable Hyper-V => open CMD as admin and type: bcdedit /set hypervisorlaunchtype off  
  
# USB Setup  
- Format USB drive as FAT32  
- Download decryptor from Telegram channel  
- Decrypt "bootx64.efi.X"  
- Create folder called EFI, create another folder called Boot and place the decrypted "bootx64.efi" inside second folder  
- Reboot system  
- If loaded successfully, our logo will appear during startup  
- Go to: http://127.0.0.1:6928/  
- Register cheat with the serial key [If you're a new user]  
- Sign in  
- Select the cheat/spoofer you want to load  
- Wait until you see a popup saying "finished"  
- Start the game  
  
# Setup UEFI  
- Disable Secure Boot  
- Delete Secure Boot Keys  
- Boot Order: UEFI USB priority then boot drive  
