# HWID Changer | HWID Spoofer

This project is a HWID (Hardware ID) changing tool designed to alter various hardware and system information. This tool makes it difficult for the computer to be recognized by changing hardware IDs and system information.

## Features

- Change disk information
- Change GUIDs
- Change MAC address
- Clear Ubisoft and Valorant cache
- Change GPU ID
- Change computer name
- Change installation ID
- Change EFI variable ID
- Change SMBIOS serial number
- Check registry keys
- Display system information

## Installation

1. Clone the repository or download the zip file:

   ```sh
   git clone https://github.com/user/hwid-changer.git
   ```

2. Open the project in a C# development environment such as Visual Studio.

3. Open the `Program.cs` file and make the necessary changes.

4. Run the project.

## Usage

In the application, you can use the following options:

1. **Disks spoofing:** Changes disk information.
2. **GUIDs spoofing:** Changes GUID information.
3. **MAC address spoofing:** Changes MAC address.
4. **Delete Ubisoft cache:** Clears Ubisoft cache.
5. **Delete Valorant cache:** Clears Valorant cache.
6. **GPU ID spoofing:** Changes GPU ID.
7. **PC name spoofing:** Changes computer name.
8. **Installation ID spoofing:** Changes installation ID.
9. **EFI variable ID spoofing:** Changes EFI variable ID.
10. **SMBIOS serial number spoofing:** Changes SMBIOS serial number.
11. **Check registry keys:** Checks registry keys.
12. **Display system data:** Displays system information.
13. **Spoof all:** Executes all commands.

Type `exit` to exit.

## Code Explanation

### CheckRegistryKeys

This method checks various registry keys to see if the specified keys exist.

### SpoofInstallationID

This method generates a new Installation ID and writes this value to the registry.

### SpoofPCName

This method generates a random computer name and writes it to various registry keys.

### RandomId and RandomMac

These methods generate random IDs and MAC addresses.

### Enable_LocalAreaConnection

This method enables or disables the local area connection.

### SpoofDisks

This method changes disk information.

### SpoofGUIDs

This method changes various GUIDs.

### UbisoftCache and DeleteValorantCache

These methods clear the cache files for the respective games.

### SpoofMAC

This method changes the MAC address.

### SpoofGPU

This method changes the GPU ID.

### SpoofEFIVariableId

This method changes the EFI variable ID.

### SpoofSMBIOSSerialNumber

This method changes the SMBIOS serial number.

### DisplaySystemData

This method displays system information.

### Menu

This method manages the user menu and calls the appropriate methods based on user input.

## Contributing

If you would like to contribute, please star the repository.

## License

This project is licensed under the MIT License. For more information, please refer to the `LICENSE` file.