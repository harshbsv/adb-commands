# adb-commands
A list of commonly used ADB commands.

adb wait-for-device          - block until device is online
adb start-server             - ensure that there is a server running
adb kill-server              - kill the server if it is running
adb get-state                - prints: offline | bootloader | device
adb get-serialno             - prints: <serial-number>
adb get-devpath              - prints: <device-path>
adb status-window            - continuously print device status for a specified device
adb remount                  - remounts the /system and /vendor (if present) partitions on the device read-write
adb reboot [bootloader|recovery] - reboots the device, optionally into the bootloader or recovery program
adb reboot-bootloader        - reboots the device into the bootloader
adb root                     - restarts the adbd daemon with root permissions
adb usb                      - restarts the adbd daemon listening on USB
adb tcpip <port>             - restarts the adbd daemon listening on TCP on the specified port
