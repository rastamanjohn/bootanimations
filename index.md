### What are boot animations?
The **boot animation** is what you see when you boot a phone. It's generally a boring **SAMSUNG** or **LG** logo, but with **root access** (or at least unlocked bootloader/custom recovery,) you can change it.

### The way it works:
The boot animation is stored in a zip named `bootanimation.zip` in `/system/media`. All that needs to be done is replace it, and there are a few ways to do so:
- **manually** replace the files with a root explorer
- replace the files with an [**app**](https://play.google.com/store/apps/details?id=com.jrummy.apps.boot.animations)
- flash a **magisk** module

The app way is recommended, as it's the most painless way.
The zip files in the [**channel**](https://t.me/bootanmtsgallery) are just the bootanimation.zip, so either you can use the app, or you can do it manually. If so you need to rename the file approprietaly, if you use the app it will do it for you. 

These zip files **are not** flashable with magisk/recovery. I might make further on a guide how to make it flashable, tho I'm sure there is one already on XDA.

Another thing the app will do is stretch the boot animation to your resolution (unless disabled this 'feature' in its settings), this can be good or bad, depending on your preference.
### Links:
- [Install:](http://telegra.ph/Install-a-bootanimation-05-07) How to install a boot animation
- [Extract:](http://telegra.ph/Extract-a-bootanimation-05-07) How to extract a boot animation
- [Index:](http://telegra.ph/Bootanimation-Index-05-08) Index of all the boot animations on the channel, sorted alphabetically
- [Gallery:](https://t.me/bootanmtsgallery) Telegram channel with pictures for every boot animation
- [App:](https://play.google.com/store/apps/details?id=com.jrummy.apps.boot.animations) What I generally use to install, has previews and backups too. Not affiliated to me in any way.

### Want to make one yourself?
[These are the **guidelines**](https://android.googlesource.com/platform/frameworks/base.git/+/master/cmds/bootanimation/FORMAT.md), kindly provided by google/android. One thing I'll add is not to compress when zipping the boot animation as it won't boot (even tho it will work in the app's preview).

### Want to contribute?
Send [me](https://t.me/rastamanjohn) any boot animation that is not on the channel and you want to share.
