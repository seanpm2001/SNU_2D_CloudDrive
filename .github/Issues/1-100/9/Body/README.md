
***

# A new vision - 2022 July

In the past week (2022, Tuesday, July 12th to 2022, Sunday, July 17th) I have been toying with a new concept for online file storage. I have decided to revive this project to fit this new vision.

The core concept is that the file service frontend should look and behave just like the desktop of an operating system (for Ubuntu+GNOME users, an example would be Nautilus/GNOME files. For MacOS users, an example would be Finder, for Windows users, an example would be Windows explorer) I have not seen any file service come as close to this as I envision. I envision it to feel so close to a desktop that it is almost like you are running a virtualized operating system, and as little like a webpage as possible. I still want to separate it from the SNU online Virtual Machine manager VMCenter. However, I expect that not everyone will run a virtual machine in their web browser.

This new vision is starting its development officially today. I have decided against using JavaScript for this, and will use something that complies with the GNU standard, and avoids the JavaScript trap, so that it will still work if JavaScript is disabled.

The new online file storage frontend will be an isolated system, with customization via skins. The default skin will be an X11 look-alike skin for the time being. Users can switch between other skins by a skin stored in their drive, or by a skin uploaded (either for permanent or temporary use) SNU Drive skins will use the `*.driveskn` file format, which is XML based.

The other variants of online file storage will be available and still developed, this will be an additional option users can use that isn't based on any existing site/service.

***
