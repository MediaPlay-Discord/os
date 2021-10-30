
# MediaPlay OS
*Not an actual operating system... yet.*

---

This is Linerly's iteration of MediaPlay OS, created using ~~Scratch~~TurboWarp.

The Scratch project file (*.sb3) is in /source.

The web version of it can be used at https://mediaplay-discord.github.io/os. It's not polished yet, but be aware that there may be some problems in the web version, these will be fixed after a while. (by using another Scratch 3 to HTML converter)

---

## Will it be an actual OS in the future?
I'm not sure about it, but let's see what I'll will decide later.

Since the Scratch 3 project file can be converted into HTML, it is theoretically possible to turn it into a desktop environment for GNU/Linux (and maybe others?) by either using WebKitGTK or Qt WebEngine (Chromium in Qt). I haven't seen someone who's making a desktop environment using web technologies though - actually no, Google did it for Chromium/Chrome OS (iirc).

Ideas.

## Techy already made MPD OS and it's fine! Why bother making a 'remastered'/another version?
This (remastered) version will include more features, including a polished installation wizard (though it may be seperated in order to reduce complexity) a new user experience, more functionalites, and more to come!

## Can I help?
Sure! You can...
- Get the Scratch project file, **load it in TurboWarp Desktop (and make sure to set the resolution in the project settings to 1366x768)**, and run the project in full-screen mode. Then, report for any defects that you found or give improvements - if you have one - in the issue tracker!
- Use the web version at https://mediaplay-discord.github.io/os, but it may slow to run or might not work on some browsers/devices (this is known, don't report it especially if you're running it on mobile). Please use a 16:9 aspect ratio, some things may not be displayed properly or don't look right while using another aspect ratio. (9:16, 1:1, ...)

**If you're going to edit the Scratch project file, here are some important things you need to know.**
- Set the project's resolution to 1366x768. (though in the web version, it's resizeable to any resolution for now)
- Always select a sprite by selecting it in the sprites section. Never select the sprite in the preview section - you may have a hard time adjusting the sprite's layer as the project gets larger.
- If you're going to make a new sprite, make sure adjust the sprite's layer too.
- After making your changes, test the project by running the project (clicking the green flag) in full-screen mode.
- Test everything in full-screen mode; make a note of the things that don't work properly, try to fix the things that doesn't work properly after testing. After that, test again in full-screen mode.
- If you don't see the sprite(s), make sure to adjust the sprite's layer as needed.

## ~~Why bother using PowerPoint? It's proprietary.~~
~~We know about this. One of us had an idea in mind to make it in Scratch - which technically has a lot more features than PowerPoint - but most of us can use PowerPoint or any other program (like LibreOffice Impress, which Linerly uses it) anyway.~~ Linerly's PowerPoint version of MediaPlay OS has been deprecated. Scratch will be used instead of PowerPoint.

## Can I submit ideas?
You can submit your ideas in the issue tracker, thanks!

## What's with MediaPlay OS and MPD OS?
I decided to change the name of the project since we're not affiliated with Discord or anything.

---

## Tools
- [TurboWarp Packager](https://packager.turbowarp.org)
- [TurboWarp Desktop](https://desktop.turbowarp.org/)

---

## Design
In my MediaPlay OS iteration, the design is somewhat similar to Android but without the top/status bar, just the dock (and the drawer - lists of apps and a search section), Microsoft Windows for the app window's title bar placement, and macOS as well just for the close button.

Due to the limitations and complexity in Scratch, the app's window will fill the whole screen, only has a close button, and with the dock handle visible but not blocking some of the things in the apps.

---

## Imagined Apps with Concepts/Mockups
*Not real; not actual functioning apps. When it gets actually made in Scratch, there will be 'errors' if you try to do something that the apps can't do due to the app's database of <something - websites, users, whatever, it will take a while to get those sources and update them regularly, but it's a small project anyway for now> - it's intentional.*
- WebPlay (web browser, might change the name some day)
- Chedia (a portmanteau of 'chat' and 'media'; a Matrix client)
- ...

You can find the concepts/mockups for the apps in https://github.com/MediaPlay-Discord/os/tree/main/extras/concepts.
