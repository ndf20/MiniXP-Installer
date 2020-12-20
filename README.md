# SwellXP Introduction
Removes all non-essential Windows XP system files (**Creates minimal installation**)

# Files
1. **xp_inst.zip** - Main installation script.
2. **vgaoem.fon** - System Font file (Only needed if it is not already located in your C:\WINDOWS\Fonts folder.)

# Installation
1. Create new NTFS partition, format and assign drive letter. (You may **not** be able to use diskmgmt.msc due to Windows XP not allowing you to shrink the size of the system partition)
2. Edit boot.ini to add another Windows installation pointing to the new partition you just created.
3. Extract and run batch script and follow instructions to install SwellXP.
