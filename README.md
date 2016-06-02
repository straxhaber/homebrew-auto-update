# Automatic updates for Homebrew

This is a little thingy that automatically calls `brew update` and
optionally `brew fetch` and `brew upgrade` on a schedule.
By default, it does so every day at 7am and sends you a notification
when something new is available.

To install, use

    brew install straxhaber/auto-update/brew-auto-update --HEAD

and then follow the instructions that are printed:

```
==> Caveats
To have launchd start straxhaber/auto-update/brew-auto-update now and restart at login:
  brew services start straxhaber/auto-update/brew-auto-update
```

The App Store preferences for checking for updates are respected, so
to turn off updating or fetching, change the settings there.

## History
This project was started by [petere](https://github.com/petere).
I forked his project to:

* enable automatic Homebrew upgrades, and
* merge improvements from
  [jsok](https://github.com/jsok/homebrew-auto-update) and
  [xakraz](https://github.com/xakraz/homebrew-auto-update).

Feel free to submit issues and pull requests with improvements.
