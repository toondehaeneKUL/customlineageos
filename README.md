# Privacy Dashboard LineageOS ROM
Adds a privileged ContentProvider which can be used by apps such as [PrivacyBuddy](https://github.com/toondehaeneKUL/privacybuddy) to visualize location access requests by other apps on the system.


## Building
This extension was built for LineageOS 19.0. Replace the content of lineage/packages/modules/Permission/PermissionController with the content inside this project /PermissionController and build as usual, for example following this guide https://wiki.lineageos.org/emulator. Only compatibility with version 19.0 was tested.

