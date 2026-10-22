# manzlio downloads

The manzlio apps, ready to install. This repository only holds the releases.

## Android

Download **[manzlio.apk](https://github.com/enyerhmotion/manzlio-downloads/releases/latest/download/manzlio.apk)** on your phone and open it ([release notes](https://github.com/enyerhmotion/manzlio-downloads/releases/latest)).
The first time, Android asks you to allow installs from your browser. Then connect the app to your manzlio server's address.
Android 7 or newer.

In the car, Android Auto lists apps installed from outside the Play Store once *Unknown sources* is on in Android Auto's developer settings (tap its version ten times to see them).

## Windows

Download **[manzlio-setup.exe](https://github.com/enyerhmotion/manzlio-downloads/releases/download/desktop/manzlio-setup.exe)** ([release notes](https://github.com/enyerhmotion/manzlio-downloads/releases/tag/desktop)) and run it. Windows 10 or 11, 64-bit.
It installs for your user, with no administrator rights. Windows may say it doesn't recognise the app, because it isn't signed with a paid certificate yet: choose *More info → Run anyway*.
The installed app finds its own updates here.

The Mac and Linux versions are on their way.

## Checking a download

Each release has a `SHA256SUMS` file. On Windows, `certutil -hashfile manzlio-setup.exe SHA256` prints the hash to compare against it. On Linux or a Mac, use `sha256sum -c SHA256SUMS`.
