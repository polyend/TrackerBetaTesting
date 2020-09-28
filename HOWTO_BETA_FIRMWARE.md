# Testing Pre-release Builds of the Tracker firmware

## Before you begin

Hi there! Are you interested in testing beta versions of the next
Tracker firmware?  Great, we're glad to hear that.  Let's just set
some expectations up-front: **beta releases are provided on an "as is"
basis**.  That means any of the following:

* they may introduce new bugs that may lead to loss of work or crashes
  during performance;

* they may introduce new features that will probably not be documented
  before the next stable release;

* they may change or remove previously existing features, both
  documented and undocumented; and

* they may change the data format of the projects or instruments you
  save, making it impossible to open them with an older firmware
  version.

If you find those risks acceptable, let's get you started!

## Download a .ptf file

You can find the latest `.ptf` files in the
[Releases](https://github.com/polyend/TrackerIssues/releases/) section
of this repository.  Note that the "Source Code" in each release doesn't
actually contain Tracker's sources but just this repository's files,
including the one you're reading now.

## Put the .ptf file on your SD card

![SD card view with the Firmware/ folder open](./images/sd-card-firmware.png)

You can use the bundled microSD USB adapter to connect the SD card to
your computer. Put the `.ptf` file in the Firmware/ folder next to other
`.pth` files.
If you erased your card and don't have the latest stable firmware, get
it from [the Polyend website](https://polyend.com/downloads/).

## Put the SD card back in your Tracker and go to Config

![Config/Firmware screen](./images/config-firmware.jpg)

In the Firmware section you'll find a "Firmware update" feature. Enter
it.

## Select the firmware you want

![Firmware selection](./images/config-firmware-selection.jpg)

After selecting the right file, press Select and wait for the upgrade to
finish.  You should see it progress through the file and restart the
device.

## In case of trouble

If your device lost power during the upgrade, the SD file was damaged,
or the firmware doesn't boot up for any other reason, download the
Polyend Tool from [the Polyend website](https://polyend.com/downloads/)
and connect your Tracker directly to your computer with a USB cable.

## If you find bugs

That's why we're testing! Report them
[here](https://github.com/polyend/TrackerIssues).