# VirtualBox

## How to create a sharing folder in a VirtualBox

- With the VirtualBox running, click the "Devices" menu and choose the "Insert Guest Additions CD image..." option. This insert a virtual CD that you can use within the guest operating system to install the Guest Additions.
- After the Guest Additions are installed, open the "Machine" menu and click the "Settings" option.
- In the “Settings” window, switch to the “Shared Folders” tab. Here you can see any shared folders you’ve set up. There are two types of shared folders. Machine Folders are permanent folders that are shared until you remove them. Transient Folders are temporary and are automatically removed when you restart or shut down the virtual machine.
- Click the “Add” button (the folder with a plus on it) to create a new shared folder.
- In the “Add Share” window, you can specify the following:
> Folder Path: This is the location of the shared folder on your host operating system.

> Folder Name: This is how the shared folder will appear inside the guest operating system.

> Read-only: By default, the virtual machine has full read-write access to the shared folder. Enable the “Read-only” checkbox if you want the virtual machine only to be able to read files from the shared folder, but not modify them.

> Auto-mount: This option makes the guest operating system attempt to automatically mount the folder when it boots.

> Make Permanent: This option makes the shared folder permanent.
- Choose "Make Permanent" and then hit the “OK” button.
- You should now see the shared folders appear as network file shares.