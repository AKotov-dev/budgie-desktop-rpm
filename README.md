# Budgie Desktop rpm packages for Mageia Linux
Budgie Desktop is a familiar, modern desktop environment.  
Project URL: https://github.com/BuddiesOfBudgie/budgie-desktop

These rpm packages is intended for Mageia-9 Linux. Unlike the original, this build uses the `Nemo` file manager, which allows you to fully work with the desktop environment. RPM packages are contained in the `rpmbuild.tar.gz` in the folder `./RPMS/x86_64`.

To set the language switch `<Alt_L>Shift` in the loaded system, you need to execute this code (regular user):
```
gsettings set org.gnome.desktop.wm.keybindings switch-input-source "['<Alt>Shift_L']"
gsettings set org.gnome.desktop.wm.keybindings switch-input-source-backward "['<Shift>Alt_L']"
``` 
The `themes` folder contains `ChromeOS` theme packages + `Windows-10` icons/cursors.

![](https://github.com/AKotov-dev/budgie-desktop-rpm/blob/main/ScreenShot.png)  

Archive `budgie-settings.tar.gz` contains a GUI for quick DE configuration. Just unzip the archive and run the `budgie_settings` file from a regular user.  
  
**Note:** I use it on my home computer and maybe it will be useful for someone as well.  
  
**Sample:** Live Flash drive `MgaRemix-9-Budgie` (RU/EN): https://cloud.mail.ru/public/oTYe/uwUio2x7f