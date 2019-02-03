# android-hosting
Free Hosting with your android phone
_Have an android device you use or maybe just lying around the house not being used?_

_Make it a bot hosting device!_

_This guide will show you how to host your very own custom created discord bot on an android device, tablet or phone._
**Read all this first!**
_Disclaimer: I am not responsible for any charges on the device, data usage, billing, charges etc. I also don't take any responsibility for any damage this method may cause to the bot, device etc. This only works on Android Devices only and does not work on IOS (iPhones). You were the one who decided to try the method. In summary, **I take no responsibility** for any sort of problems that you may occur or trouble. 

**IMPORTANT: BACKUP YOUR BOT PROJECT PATH'S**. _I don't know if something will go wrong but you never know. So back them up. You should already be doing so if you're on beta. The reason I warn this is because we are touching the bot project folder a bit, copying/ moving files etc._

Also note, this takes  some battery usage, So it may be **recommended** to use on a device that is plugged in constantly.  Though this depends on the device.
**Speed is also a factor, the slower the device, the worse the performance is on the bot itself. same with the amount of servers. So please don't try and run 500+ servers..**
So please have a reasonable fast phone/tablet. mid-range phone/tablet at least. Results vary on every device

With that disclaimer out of the way let's begin with the actual guide
**1. Preparing**
First, go to your bot directory, To find the bot directory simply go into dbm, project &gt; open project directory

[image](https://i.imgur.com/6IAybLg.png)

For this, I'll be using Ted (_cause why not!_)
[image](https://i.imgur.com/bkJW3AZ.png)

When DBM opens the project folder, go back one so that you are out of the bot's directory folder.
Now you should see your bots name. (1st picture)

Now here is what we need for the guide.
**1. Requirements**
You will need [7zip PC.](https://www.7-zip.org/download.html)
You will need an app called Dory - node.js
Instaled on the phone/tablet. [Link](https://play.google.com/store/apps/details?id=io.tempage.dorynode&amp;hl=en)

**A device running Android 5 or higher**
You will need a file manager. I recommend using [ES File Explorer.](https://play.google.com/store/apps/details?id=com.estrongs.android.pop)
Once you have those requirements done, we can move on to section 2.

**2. Transferring files.**
The first step is to plug in your device to the computer. Once you done that, your device should be connected and you should be able to browse it's files. If for some reason it doesn't, here's a guide for that. [link](https://www.howtogeek.com/195607/how-to-get-your-android-device-to-show-up-in-file-explorer-if-it-isnt/)

Now right go back to the other folder and right-click on your bot's name, and move on down to the 7zip option 
[img](https://i.imgur.com/tqEAJDX.png)
then click on add to "yourbotname.zip"
Let 7zip do its thing and once it's done, you'll see a .zip file appear.
Copy that zip, go to the file explorer of the device, navigate to the downloads folder and paste the .zip in it.
[img](https://i.imgur.com/Qj9Y5ZJ.png)
**Please use the downloads folder, it's easier k! Do not place the bot zip anywhere else!**

The reason why we did zip and compressed is well, it compresses it
If you were to just drag the folder in uncompressed it would take 3+ hours to copy over. I don't think you'll want to wait that long, so that's why we used compression.

Once done, we can now move on to the device side, make sure the zip is on the device before unplugging!

[img](https://i.imgur.com/yNNkgzI.jpg)
Open ES File Explorer
Navigate with the app to the downloads folder
[img](https://i.imgur.com/gkxWQYZ.png)
Tap on the zip folder.
_If you get a Select Message_
Click on ES Zip Folder

If you don't get a Select Message, Keep going.
Now, you will see the same folder name, tap and hold, Once you have done that, click on extract
[img](https://i.imgur.com/w7SpD0f.png)
Leave it like this and tap Okay and let it extract.
Once done, exit the ES file explorer app and enter the node.js app

In the node.js app tap the red + icon
Select Add Directory(package.json's main)
Now navigate to the Download Folder
tap the bot folder's name. Keep tapping the name till you get folders like actions, data, fonts etc.
Once you see those folders, don't tap on anything else, but tap on **Select Directory**
Once done, it'll send you back to the app and you'll see your bot directory, select OPEN to verify.
Just make sure the package.json has discord-bot-maker bot etc. If it does, just back out of it.

**Now just tap start and the bot will start up. That's it!**

**If you want the bot to stay on, some devices may shut off wifi/cellular services when the device is locked, to prevent that tap on the 3 lines**

Here are some options
**Start on boot - Bot will start on bootup of device**
**Start on the update - Either if files updated or the app update, it'll start the bot up**
**WIFI Lock** - Ensure that the WiFi radio will remain active when the phone is idle.
WAKE LOCK - Not sure if it's a good idea, keeps the device from sleeping.
If you go back and see the options of start, stop etc, you might notice settings and an STD out
STD out is the logs, view those to see bot logs
Settings, here are some options
Live Reload - Reloads the bot if files are updated.
Auto Restart - If bot crashes or goes offline, reboots bot.
Timeout - Unsure..

Leave the rest of the settings as is.

**Done! You now have the bot running on your device, If you need help with anything, DM on discord
xtazy#0001**
Extra
Updating bot files is more of a process but just follow the same steps, but ignore compression and 7zip and the other stuff in this guide, just drag the  commands.json and events.json to the device, then use ES file explorer to replace the files in the bot folder on the device. Reboot the bot.
