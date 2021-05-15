# adb-commands
A list of commonly used ADB commands.

adb wait-for-device          - block until device is online<br/>
adb start-server             - ensure that there is a server running<br/>
adb kill-server              - kill the server if it is running<br/>
adb get-state                - prints: offline | bootloader | device<br/>
adb get-serialno             - prints: "<serial-number>"<br/>
adb get-devpath              - prints: "<device-path>"<br/>
adb status-window            - continuously print device status for a specified device<br/>
adb remount                  - remounts the /system and /vendor (if present) partitions on the device read-write<br/>
adb reboot [bootloader|recovery] - reboots the device, optionally into the bootloader or recovery program<br/>
adb reboot-bootloader        - reboots the device into the bootloader<br/>
adb root                     - restarts the adbd daemon with root permissions<br/>
adb usb                      - restarts the adbd daemon listening on USB<br/>
adb tcpip <port>             - restarts the adbd daemon listening on TCP on the specified port<br/>
