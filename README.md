EJECT ALL DRIVES 1.1

This is a simple Mac App that safely ejects external drives, SD cards and opens dmg with 1 click.  No more interrupting your work to open Finder and manually eject each open external drive, dmg or SD card.  Use at your own risk.  Originally written in Apple Automator but this version is vibe coded using ChatGPT Work.  This took an astounding 1.7 million tokens!

1. Double-click the app. When the error pop-up appears click Cancel or OK. 
2. Navigate to the Apple Menu > System Settings > Privacy & Security. 
3. Scroll down to the Security section. 
4. Look for a note stating the app was blocked, and click the Open Anyway button. 
5. Enter your Mac password or use Touch ID to confirm.  You only need to do this once after install.

The app immediately disconnects eligible external drives, non-startup internal volumes, and network shares. Offline system installations are eligible. The running macOS startup system remains protected: it cannot be disconnected while this Mac is running.

Ejected: the whole drive is offline and safe to unplug.
Unmounted: that particular volume is unmounted; other volumes on the same drive may still be mounted. Disconnect physical hardware only after every volume on it is unmounted.
Disconnected: the network share is unmounted.
Protected: the active macOS system or the volume hosting this running app.
Not disconnected / inspection failure: keep the drive connected and review the error.

Busy drives are never forced. Close files or apps using them, then select Eject Again.
Copy Results copies the displayed results and error text for troubleshooting.

This version finds mounted volumes directly, without requiring optional hardware fields. Missing metadata now uses a safe volume-unmount fallback or displays an explanation instead of silently hiding the drive.

The app is ad-hoc signed, not Apple-notarized. If macOS blocks first launch, use the normal Privacy & Security approval for this trusted local app if offered. Do not disable Gatekeeper.

Requires macOS 13+. Native Apple silicon code supports M5 Macs; an Intel slice is included. No administrator password or privileged helper is requested. macOS permission denials are shown as failures.
