# mailnag-gnome-shell
Mailnag GNOME-Shell extension.

#### Features
* Notifies about new mails via the messaging tray (including a counter badge).
* Shows an indicator in the top panel (including counter badge and popup menu).

Help is very appreciated!

#### Installation
This extension requires the Mailnag daemon from the [mailnag-next](https://github.com/pulb/mailnag/tree/mailnag-next) branch.
Prior to installation, run `mailnag-config` and ensure that the *libnotify* plugin is disabled.

##### Requirements
* vala (at compiletime only)
* libfolks
* mailnag

To install the extension type `make install prefix=<INSTALL_PREFIX>`  
in a terminal (e.g. `make install prefix=/usr>`).  
That's it. Now fire up `gnome-tweak-tool` and enable the extension.  

__Note:__ If you want to install to *~/.local* (*prefix=~/.local*),  
make sure *~/.local/bin* is included in your $PATH (alternatively copy  
*~/.local/bin/aggregate-avatars* to *~/.local/share/gnome-shell/extensions/mailnag@zulu99-gmx-net*).

#### Screenshots
![Screenshot](https://raw.github.com/pulb/mailnag-gnome-shell/docs/docs/screenshots/mailnag-gnome-shell.png)
