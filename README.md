# vbox-osx-menubar

![dropdown-shot](screenshots/dropdown.png)

This is a clone of the [statusmenus][0] project hosted on SourceForge.

It has only a couple of patches (see commits) to remove the shadows and switch
to light icons for the dark menubar in OSX 10.10.

You can configure VMs to run in headless mode from the sub-menu:

![dropdown-shot](screenshots/headless.png)

[0]: https://sourceforge.net/projects/statusmenus/

## aidandj updates

* Update for MacOS 10.15
* Remove optimization (couldn't find file)
* Release a binary
* Add license

## How to run at startup

1. Move the `VirtualBox Menulet.app` out of your downloads folder. (I put it in `Applications/Utilities`)
2. Open System Preferences
3. Open `Users & Groups`
4. Select your user
5. Click on `Login Items`
6. Click on the `+` icon
7. Navigate to `VirtualBox Menulet.app` and select it

## Error on opening

There is a good chance you will get an error like the one below

![catalina-error](screenshots/osx-catalina-error.png)

To bypass this, hold <kbd>⌃ Control</kbd> and click on the `VirtualBox Menulet.app` item. Then select `Open`, and the click `Open` again in the file dialog.