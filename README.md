# thinkpadp52-bigsur
Thinkpad P52 macOS Big Sur Opencore

i7-8850H w/Quadro P3200

For Monterey, delete intelbluetoothinjector from kext folder and config.plist

Working

    Intel WiFi
    Intel Bluetooth
    Brightness Control
    Intel HD 630
    Touchpad gestures
    Built In Audio
    USB-A ports
 
Not Working

    Nvidia graphics
    hdmi out (because it's routed to dgpu)
  
Not Tested

    3.5mm Audio
    Thunderbolt ports (probably works, used USBMap to fix usb)
    Mini Display Port (probably routed to nvidia as well, so no go)
