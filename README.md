# macos-virtual-display

> Add virtual displays to achieve functionality similar to Sidecar/Duet Display/Luna Display.

## Installing

Copy .kext & .framework to /System/Libraries/E with the proper permission & ownership. Reboot.
EWProxyFramebuffer.app enables/disables the virtual display

## Usage

1. Create a virtual display on you mac using the attached driver (kext) and app.
2. Enable Screen Sharing or Remote Management (System Preferences/Sharing)
3. On the machine (computer or mobile device) that has the screen (connected to it) you want to use as an external monitor connect to using vnc (Screen Sharing)

## References

- [Share Virtual Display (like Sidecar) on Mojave](https://www.tonymacx86.com/threads/share-virtual-display-like-sidecar-on-mojave.285494/)
