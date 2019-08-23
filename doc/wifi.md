# Configuring WiFi

Create a file named wpa_supplicant.conf on the FAT partition of the SD card as follows:

    ctrl_interface=/var/run/wpa_supplicant
    ap_scan=1

    network={
        ssid="my_network_name"
        psk="my_network_password"
    }
