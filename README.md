# How to install MacOS on Windows

***

Useful Links

* [Try macOS on Windows 11](https://www.youtube.com/watch?v=fcf0NIFsoo0)


# Install VirtualBox

* [VirtualBox](https://www.virtualbox.org/)
* https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170



# 2. Download MacOS ISO
https://archive.org/details/macos-collection

# 3. Create a new Viruta machine
ed "%programfiles%\Oracle\VirtualBox\"
VBoxManage modifyvm "VM name" --cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff
VBoxManage setextradata "VM name"
"BoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac11, 3"
VBoxManage setextradata "VM name"
"VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0'
VBoxManage setextradata "VM name"
"VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "NetVN"
VBoxManage setextradata "VM name" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedple:
VBoxManage setextradata
"VM name"
VBoxManage modifyvm "VM_name"
"VBoxInternal/Devices/smc/0/Config/GetKeyFromealSMC"1
--cpu-profile "Intel Xeon X5482 3.20GHz"
VBoxManage setextradata
"VM_name" "VBoxInternal/TM/TSCMode" "RealTSCOffset
