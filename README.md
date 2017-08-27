# fcitx-SlackBuild-live
My modified SlackBuild for fcitx (IME) to be installed on LiveSlak (Slackware Live)

**This script is just included of some configuration files which need to be installed to a live OS (since one has no chance to make his/her changes persistent in the live OS)**

## Changes I made

- fcitx-autostart
  - make fcitx really autostart when the DE starts (invoked by fcitx-autostart.desktop in `/etc/X11/xdg/autostart` )

- config & profile
  - let it smartly select **libpinyin** as its input method (without enable it manually)
  - other small tweaks

**FEEL FREE to tweak as you like!**

