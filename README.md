# usbkill

usbkill waits for a change on your usb ports, then immediately kills your computer.  Anti forensic, usb -> kill


Unfinished project! Expect improvements to come.

But it does work and is effective.

To run: sudo python3 usbkill.py


# Why?
In case the police comes busting in, or steals your laptop from you when you are at a public library (as with Ross).
The police will use a `mouse jiggler' [0] to keep the screensaver and sleep mode from activating. If this happens you would like your computer to shut down immediately. Additionally, you may use a cord to attach a usb key to your wrist. Then insert the key into your computer and start usbkill. If they then steal your computer, the usb will be removed and the computer shuts down immediately.

Custom commands for when a usb change is observed will be implemented later.

Make sure to use full disk encryption! Otherwise they will get in anyway. 

# Contact
hephaestos@riseup.net - 8764 EF6F D5C1 7838 8D10 E061 CF84 9CE5 42D0 B12B

[0] http://www.amazon.com/Cru-dataport-Jiggler-Automatic-keyboard-Activity/dp/B00MTZY7Y4/ref=pd_bxgy_pc_text_y/190-3944818-7671348