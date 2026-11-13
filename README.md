<p align="center">
  <img src="icon.png" width="128" alt="Touchy icon">
</p>

<h1 align="center">Touchy</h1>

<p align="center"><strong>Touch Screen &amp; Logo Toggle</strong></p>

<p align="center">
  Menu bar switches for the MacBook Pro PROLED XDR's hardware extras:<br>
  the glowing Apple logo and the touch screen.<br><br>
  <a href="https://touchymac.com">touchymac.com</a>
</p>

---

This repository hosts Touchy's signed releases and its issue tracker.

## Download

**[Download the latest version](https://github.com/taylorbrauer/touchy-releases/releases/latest/download/Touchy.zip)**. It's free, needs macOS 27.2 or later, and is signed and notarized by Apple.

Or with [Homebrew](https://brew.sh):

```sh
brew install taylorbrauer/tap/touchy
```

Release notes are on the [Releases page](https://github.com/taylorbrauer/touchy-releases/releases).

## Install

1. Unzip the download and drag **Touchy.app** into **Applications**, then open it.
2. Touchy's setup window opens on first launch. Click **Allow**, then switch
   **Touchy** on in System Settings → General → Login Items & Extensions.
   This one-time approval lets the logo switch work without a password prompt.
3. Click **Grant Access** and approve the standard **Accessibility** prompt.
   Touchy uses it only to flip Apple's own Touch switch for you. That's the
   last thing macOS asks.

## What it does

- **Apple logo glow**: turn the illuminated Apple logo on the lid on or off
  (MacBook Pro PROLED XDR).
- **Touch**: enable or disable the built-in touch screen without opening
  System Settings.
- **Global shortcuts**: **⌃⌥T** toggles touch and **⌃⌥L** toggles the logo
  glow, from any app.

- **Updates**: Touchy tells you when a new version is out and installs it
  for you, if you choose to.

Touchy has no analytics and sends nothing about you or your Mac. Its only
network connection is the update check, which asks your permission first and
can be turned off in Settings.

## Support

Touchy is free. If it's useful to you,
[subscribe on YouTube](https://www.youtube.com/@taylorbrauer?sub_confirmation=1)
or [buy me a coffee](https://buymeacoffee.com/taylorbrauer).

## Problems or ideas

[Open an issue](https://github.com/taylorbrauer/touchy-releases/issues/new/choose).
For a touch-switch problem, attach `~/Library/Logs/Touchy-axtree.txt`
and include your macOS version and system language.

## Uninstall

Quit the app, remove its entry in System Settings → General → Login Items &
Extensions, then drag it to the Trash. If you installed with Homebrew,
`brew uninstall --zap touchy` does all of that.
