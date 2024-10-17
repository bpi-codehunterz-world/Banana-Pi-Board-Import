# This are the board cofig files for banana pi m2 berry & banana pi m2 ultra!"


# Directory & Files
```
└── bananapi
    ├── board
    │   ├── bpi-m1
    │   ├── bpi-m1p
    │   ├── bpi-m2
    │   ├── bpi-m2m
    │   ├── bpi-m2p
    │   ├── bpi-m2p-h5
    │   ├── bpi-m2u
    │   ├── bpi-m2z
    │   ├── bpi-m3
    │   ├── bpi-m64
    │   ├── bpi-r1
    │   ├── bpi-r18-avs
    │   ├── bpi-r2
    │   ├── bpi-rpi
    │   └── bpi-w2
    ├── board.sh
    ├── bpi-autorun.d
    │   ├── S02-hung_task.sh
    │   ├── S10-audio-bpi-m2m.sh
    │   ├── S10-audio-bpi-m2u.sh
    │   ├── S10-audio-bpi-m3.sh
    │   ├── S10-audio-bpi-m64.sh
    │   ├── S10-audio-bpi-r18-avs.sh
    │   ├── S80-ipaddress.sh
    │   ├── bpi-autorun.sh
    │   ├── rc.local
    │   ├── rc.local.ubuntu_16.04
    │   ├── s05-sun8i-corekeeper.sh
    │   ├── s20-raspbian.sh
    │   ├── s30-adbd.sh
    │   └── s90-user-auto.sh
    ├── bpi-init.d
    │   ├── S00-bpi-hw-auto.sh
    │   ├── S01-bpi-sw-ld.sh
    │   ├── S01-fbdev-bpi-w2.sh
    │   ├── S02-bpi-hw-gpu.sh
    │   ├── S03-bpi-sw-gpu.sh
    │   ├── S10-bpi-hw-camera.sh
    │   ├── S10-bpi-hw-wifi.sh
    │   ├── bpi-init.sh
    │   ├── s05-rfkill.sh
    │   ├── s06-docker.sh
    │   ├── s10-bpi-hw-ir.sh
    │   ├── s10-bpi-hw-touch.sh
    │   └── s90-bpi-hw-bt.sh
    └── others
        ├── etc
        │   ├── X11
        │   │   ├── Xsession.d
        │   │   │   └── 90vdpau
        │   │   └── xorg.conf
        │   ├── environment
        │   ├── lightdm
        │   │   └── lightdm.conf
        │   ├── mpv
        │   │   └── mpv.conf
        │   ├── network
        │   │   └── interfaces.d
        │   │       ├── eth0
        │   │       └── lo
        │   ├── profile.d
        │   │   └── vdpau.sh
        │   ├── pulse
        │   │   └── default.pa
        │   └── udev
        │       └── rules.d
        │           ├── 50-cedar.rules
        │           ├── 50-disp.rules
        │           ├── 50-ion.rules
        │           ├── 50-mali.rules
        │           └── 71-axp-power-button.rules
        └── usr
            ├── lib
            │   ├── libMali.so
            │   ├── libUMP.so
            │   ├── mali
            │   │   ├── libEGL.so
            │   │   ├── libEGL.so.1
            │   │   ├── libEGL.so.1.4
            │   │   ├── libGLESv1_CM.so
            │   │   ├── libGLESv1_CM.so.1
            │   │   ├── libGLESv1_CM.so.1.1
            │   │   ├── libGLESv2.so
            │   │   ├── libGLESv2.so.2
            │   │   ├── libGLESv2.so.2.0
            │   │   └── libMali.so
            │   └── xorg
            │       └── modules
            │           └── drivers
            │               ├── fbturbo_drv.la
            │               └── fbturbo_drv.so
            ├── local
            │   └── bin
            │       ├── bpi-bt-on
            │       ├── bpi-bt-patch
            │       ├── brcm_bt_reset
            │       ├── brcm_patchram_plus
            │       └── bt_reset.sh
            └── share
                └── lightdm
                    └── lightdm.conf.d
                        ├── 50-xserver-command.conf
                        └── 55-xserver-command-pvr.conf

28 directories, 79 files
```