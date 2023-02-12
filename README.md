# Disclaimer
*I do not own any rights to any software provided and I am not an original creator and/or owner of Ventoy or MediCat USB.*
# Description
This is a Ventoy customisation to a MediCat USB v21.12.

# Customisations
<details>
<summary>New icons added</summary>

- Clonezilla icon
- Gandalfs WinPE icon
- Hirens Boot CD WinPE
- Kali Linux
- Linux Mint
- Windows 7
- Windows XP
- Windows + Linux
- x64
- x86
</details>

<details>
<summary>ventoy.json changes</summary>

- Live OS changes:
    - Added Gandalfs WinPE
    - Added Hirens WinPE
    - Added Kali Linux Live
- Partitioning Tools changes:
    - Added Clonezilla
- "Install Windows" renamed to "Install OS", changed icons
    - Added Linux OS directory
        - Added Kali Linux Install
        - Added Linux Mint Install
        - Added Ubuntu Install
    - Added Windows directoty
        - Added x86(32bit) architecture OS folder:
            - Windows 7
            - Windows 10
            - Windows 10 LTSC
            - Windows XP
        - Added x64(64bit) architecture OS folder:
            - Windows 7
            - Windows 8.1
            - Windows 10
            - Windows 10 LTSC
            - Windows 11
- Added "Delete Ventoy SecureBoot Key"
</details>

# Repo structure
- `plain_ventoy_folder` contains all necessary files for Ventoy to work. However, it **DOES NOT** contain the drive structure. This may lead to missing icons and erroneous behaviour of Ventoy. Use with caution.
- `structured_drive_folder` contains all necessary files for Ventoy to work along with a drive structure. Each folder containing `.placeholder` needs to have a file(s) specified within the file itself.

# Links
- Official MediCat USB website: [Official Medicat website](https://medicatusb.com/)
- Official forum page of MediCat USB with discussions: [Official Medicat forum page](https://gbatemp.net/threads/medicat-usb-a-multiboot-linux-usb-for-pc-repair.361577/)
- Ventoy official page: [Official Ventoy website](https://www.ventoy.net/en/index.html)
- Ventoy GitHub repo: [Official Ventoy repo](https://github.com/ventoy/Ventoy)