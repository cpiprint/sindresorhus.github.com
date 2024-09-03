---
title: Supercharge
subtitle: Elevate your Mac experience
pubDate: 2024-09-29
platforms:
  - macOS
isPaid: true
mainLinks:
  'Download': https://sindresorhus.gumroad.com/l/supercharge?wanted=true
# olderMacOSVersions:
#   - '15
feedbackNote: |
  Make sure you are on Supercharge 1.0.1 or later. There was an issue with toggling dark mode in earlier versions.
---

<sup>Requires macOS 15+</sup>

Improve your Mac experience with a bunch of useful functionality:

- Hide all windows <sup>(aka. boss mode)</sup>
- Show the [menu bar window](https://github.com/user-attachments/assets/1b8e2e12-187a-4d32-8ba3-c13f154de9e0) for the Passwords app with a keyboard shortcut
- Toggle Finder with a keyboard shortcut <sup>(aka. [visor mode](https://totalfinder.binaryage.com/visor))</sup>
- Finder: Move files to the trash with <kbd>Delete</kbd> instead of <kbd>Command+Delete</kbd>
- Finder: Open files with <kbd>Return</kbd>
- Toggle dark mode
- Toggle low power mode
- Clear clipboard
- Add [Dock spacers](#dock-spacers)
- *More planned…*

This is my playground for supercharging macOS. It's just the start. Come along for the ride.

---

You may also like my [Shareful](/shareful), [Menu Bar Spacing](/menu-bar-spacing). and [Command X](/command-x) apps.

---

### Trial

Try the fully functional trial [here](https://www.dropbox.com/scl/fi/nya501wysnqx622wzeq0e/Supercharge-1.1.0-trial-1727780947.zip?rlkey=hcu84rxz8kuqqwz4dogxbf16r&raw=1). The only limitation is a reminder to buy the app every 12 hours, and no automatic updates. All data and settings carry over if you buy it.

### Tips

#### Troubleshooting {#troubleshooting}

- Ensure you are on the latest version (click the “Check for Updates” button).
- Restart your computer.
- Quit the app, and run this command in the Terminal app:
	```sh
	tccutil reset All com.sindresorhus.Supercharge
	```

#### Tricks

Some things you can already do that you may not know about:

- Hide app windows by <kbd>Option</kbd>-clicking on the app's Dock icon.
- Show Control Center by pressing <kbd>Fn+C</kbd>.
- Toggle a specific VPN using a keyboard shortcut with Shortcuts. Add [this shortcut](https://www.icloud.com/shortcuts/a0c3171fe98a4379b8197299a84b060e) and set the VPN parameter and a keyboard shortcut.

### Frequently Asked Questions {#faq}

#### I have a feature request, bug report, or some feedback

Click the feedback button in the app or [send it here.](https://sindresorhus.com/feedback?product=Supercharge&referrer=Website-FAQ)

Some things are not possible though:

- [Removing the Trash icon in the Dock.](https://apple.stackexchange.com/a/454812/2363)


#### The app does not show up in the menu bar

macOS hides menu bar apps when there is no space left in the menu bar. This is a common problem on MacBooks with a notch. Try quitting some other menu bar apps to free up space. If this does not solve it, try quitting Bartender/Ice if you have it installed.

You may also have disabled the “Show menu bar icon” setting, which hides the menu bar icon. Launch the app again to show the main window.

#### I can already do this with the command-line, BetterTouchTool, Keyboard Maestro, etc.

Supercharge offers a simpler, more user-friendly approach. It's designed for users who want quick access to useful features without the complexity of scripting or configuring advanced tools. Supercharge provides a curated set of enhancements that work right out of the box, saving you time and effort in setup and maintenance. If you prefer more granular control and don't mind the setup process, those other tools might be a better fit for you.

#### What are Dock spacers? {#dock-spacers}

Dock spacers are [invisible gaps](https://res.cloudinary.com/cpenned/image/upload/f_auto,w_auto/v1636732613/Blog/post-images/20211112-dock.jpg) you can add to your Mac's Dock. They help organize your apps into groups, improving visual clarity. Supercharge lets you easily add these spacers, giving you better control over your Dock's layout.

#### Can I add custom actions to the app?

As of now, the app focuses on providing a curated set of built-in features for enhancing your Mac experience. I'm happy to consider requests.

#### Can you add a certain toggle?

I'm happy to consider requests, but I don't intend for this app to turn into a “toggler” app. I have just provided some commonly needed toggles.

Some toggles I don't plan to add:

- AirPods
- Keep awake *(check out [Lungo](/lungo))*

#### Why is this not in the App Store?

Much of the functionality would not be possible in the App Store because of sandboxing.

#### Can you make <kbd>Command+X</kbd> cut files in Finder?

See my [Command X](/command-x) app.

#### [More FAQs…](/apps/faq)

<!-- ### Older Versions

- [] for macOS 14

These are free for everyone but they will not run on newer macOS versions.
 -->
