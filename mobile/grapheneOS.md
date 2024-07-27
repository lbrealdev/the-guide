# GrapheneOS Setup guide

## Pre-requisites

Source:

- [GrapheneOS - Web installer](https://grapheneos.org/install/web)

#### Officially supported browsers for the web install method:

- Chromium (outside Ubuntu, since they ship a broken Snap package without working WebUSB)
- Vanadium (GrapheneOS)
- Google Chrome
- Microsoft Edge
- Brave (with Brave Shields disabled, since it caps storage usage at a low value to avoid fingerprinting available storage)

#### Pixel

- Google Pixel 7/9 generation
- Make sure that Pixel has the latest system updates

Be sure to apply all necessary updates, after reboot, go back to check if there is any updates available, if there is, update until there is no updates available.

Once all updates are installed, you should see this:

```markdown
Your system is up to date

Android version: 14
Android security update: July 5, 2024

Last sucessful check for update: 12:40 AM
```

This indicates that your Pixel is fully updated.

#### Developer mode / OEM unlocking

OEM unlocking needs to be enabled from within the operating system.

Enable the developer options menu by going to Settings > About phone/tablet and repeatedly pressing the Build number menu entry until developer mode is enabled.

To be more accurate press and drop, then press 5 times `Build number` until the developer mode is activated.

Once enabled the Developer mode, go to Settings > System > Developer options and toggle on the OEM unlocking setting. 

#### Linux dependencies

See this section of GrapheneOS documentation:

- [GrapheneOS - Flashing as non-root](https://grapheneos.org/install/web#flashing-as-non-root)

```shell
sudo apt install android-sdk-platform-tools-common
```

#### Booting into the bootloader interface and Connecting the device

Restart the phone and press and hold the volume down button while the device restarts.

Once you are in the bootloader interface, connect the USB-C cable to your phone.

#### Unlocking the bootloader

// to do

```markdown
Bootloader unlocked.
```

#### Download factory images

// to do

```markdown
Downloaded lynx-factory-2024071600.zip release.
```

#### Flashing factory images

// to do

Once finished you should see this message:

```markdown
Flashed lynx-factory-2024071600.zip to device.
```

#### Locking the bootloader

// to do

```markdown
Bootloader locked.
```

### GrapheneOS guides

- [21ideas - GrapheneOS: De-Google your phone and improve your privacy](https://21ideas.org/en/grapheneos/)
- [Bitcoiner - GrapheneOS - De-Google your phone and improve your privacy](https://bitcoiner.guide/grapheneos/)
- [Instalación de GrapheneOS en un Google Pixel 7a](https://www.manelrodero.com/blog/instalacion-de-grapheneos-en-un-google-pixel-7a)
- [Instalar Graphene OS en Google Pixel 6 en Menos de 10 Minutos – Privacidad Máxima #01](https://www.youtube.com/watch?v=KuE6ROGxp_A)

--------------------------

### GrapheneOS topics

- https://grapheneos.org/usage#esim-support
- https://grapheneos.org/usage#banking-apps
- https://grapheneos.org/usage#sandboxed-google-play-installation
- https://privsec.dev/posts/android/banking-applications-compatibility-with-grapheneos/
- https://akc3n.page/posts/banking-app-issues/
- https://github.com/Peter-Easton/GrapheneOS-Knowledge