# VirtualBox

## How to create a sharing folder in a VirtualBox

- With the VirtualBox running, click the "Devices" menu and choose the "Insert Guest Additions CD image..." option. This insert a virtual CD that you can use within the guest operating system to install the Guest Additions.
- After the Guest Additions are installed, open the "Machine" menu and click the "Settings" option.
- In the “Settings” window, switch to the “Shared Folders” tab. Here you can see any shared folders you’ve set up. There are two types of shared folders. Machine Folders are permanent folders that are shared until you remove them. Transient Folders are temporary and are automatically removed when you restart or shut down the virtual machine.
- Click the “Add” button (the folder with a plus on it) to create a new shared folder.
- In the “Add Share” window, you can specify options such as "Folder Path", "Folder Name", "Read-only", "Auto-mount", or "Make Permanent".
- Specify "Folder Path" and "Folder Name", then choose "Auto-mount" and "Make Permanent" and hit the “OK” button.
- You should now see the shared folders appear in /media/<your_username>/sf_<host_shared_folder_name>.