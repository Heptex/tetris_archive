# CMF PHONE 1 archive
* Unmodified CMF PHONE 1 OTA images archive

## Downloads
Downloads are tagged with `POST_OTA_VERSION`, NothingOS version,
[here](https://github.com/heptex/tetris_archive/releases).

Logical partition images are uploaded separately, marked `-logical`,
so that other images can be downloaded quickly if needed.

## Usage
While this is a collection of unmodified images, you still need to have the bootloader unlocked.

You can re-lock the bootloader after flashing images.

Please download and use the latest fastboot [directly from Google](https://developer.android.com/tools/releases/platform-tools).

 * **fastboot**

To flash the stock, unmodified images with fastboot, extract the files using 7z and
use [Tetris_fastboot_flasher](https://github.com/spike0en/Nothing_fastboot_flasher/tree/tetris).

## Integrity check
You can check downloaded file's integrity with one the following commands:

``` bash
md5sum -c *-hash.md5
sha1sum -c *-hash.sha1
sha256sum -c *-hash.sha256
xxh128sum -c *-hash.xxh128
```

xxh128 is usually the fastest.

### Thanks to
[luk1337](https://github.com/luk1337/oplus_archive)
[arter97](https://github.com/arter97/nothing_archive)
[spike0en](https://github.com/spike0en/Pong_Archive)
