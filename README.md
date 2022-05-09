```
███╗   ███╗ ██████╗    ███████╗███╗   ██╗██╗██████╗ ███████╗██████╗ 
████╗ ████║██╔════╝    ██╔════╝████╗  ██║██║██╔══██╗██╔════╝██╔══██╗
██╔████╔██║██║         ███████╗██╔██╗ ██║██║██████╔╝█████╗  ██████╔╝
██║╚██╔╝██║██║         ╚════██║██║╚██╗██║██║██╔═══╝ ██╔══╝  ██╔══██╗
██║ ╚═╝ ██║╚██████╗    ███████║██║ ╚████║██║██║     ███████╗██║  ██║
╚═╝     ╚═╝ ╚═════╝    ╚══════╝╚═╝  ╚═══╝╚═╝╚═╝     ╚══════╝╚═╝  ╚═╝
                                                                    
```

```sh
A rather short but comprehensive guide about installing "MCSniperGO" on Windows with minimal technological expertise.
```

-------------------------------------------

# **I. Introduction**

MCSniperGO is a sniper designed in GOLANG. It works splendidly and can be downloaded for free [here](https://github.com/Kqzz/MCsniperGO). This sniper was developed by Kqzz so all credit goes to him and all other contributors listed on the repository. Although the sniper does indeed have a guide in its README.md, I wanted to make a shorter and more concise one for newer snipers. This guide was made strictly for Windows users. Warning however, Mojang has publicly announced that they [condemn sniping using bots or other automated tools](https://twitter.com/Mojang_Ined/status/1448652087043133440) so proceed with caution. Mojang doesn't strictly enforce this decision but it's still good to be cautious nonetheless.

This process should take 7 minutes or less.


# **II. Downloading the Sniper**

Before downloading the sniper, install Python on your device if you haven't already. You may choose to skip this step and revisit it later if you are having issues. Python can be downloaded [here](https://www.python.org/downloads/), any version above 3.7 should work.

> While it might seem normal to download the sniper via the `Download ZIP` button, this is not the case.

Scroll down to the `README.md` section of the repository to locate the `Releases` hyperlink.

![https://i.gyazo.com/f0e00aac7f1e419401c263ff70d8a92d.png](https://i.gyazo.com/f0e00aac7f1e419401c263ff70d8a92d.png)

-------------------------------------------
This guide was strictly made for Windows devices. Select one of the Windows downloads to continue with the installation:

![https://i.gyazo.com/b740decb7afe499e6ab5c7f947e77f7c.png](https://i.gyazo.com/b740decb7afe499e6ab5c7f947e77f7c.png)

-------------------------------------------
# **III. Preparing the Sniper**

You should now have an `.exe` file. Do not interact with it yet; first, you'll want to make a folder for it. Right-click on your desktop and create a new folder. Name it whatever you wish. Place the `.exe` file in the folder and then double-click it. Close the program and analyze your folder. It should look like this (or similar):

![https://i.gyazo.com/5ab1a1c49c7268844fd055c10ea82ded.png](https://i.gyazo.com/5ab1a1c49c7268844fd055c10ea82ded.png)

> Your `logs` folder might only appear after you've attempted several snipes.

-------------------------------------------

Your sniper is ready to be used.

-------------------------------------------
# **IV. Authenticating your Account**

> The sniper requires access to your account in order to snipe. There is no way for a sniper to make a name-change request without access to your account.

While MCSniperGO supports multiple methods of authenticating your account, the most efficacious method involves your `auth token`. MCSniperGO might fail to authenticate your account if you decide to supply raw account login credentials. 

There are two approaches to getting your `auth token`. Approach 1 can be done by following the instructions [here](https://kqzz.github.io/mc-bearer-token/). This webpage was also created by Kqzz and full credit goes to him.

The second approach (which I tend to use) involves a quick manual fetching of the `auth token`. 

### **Step 1: Open Minecraft.net**

![https://i.gyazo.com/9722ad75585e658a094f033a2c43d93a.png](https://i.gyazo.com/9722ad75585e658a094f033a2c43d93a.png)

-------------------------------------------

Right-click and press `inspect`. By default, you should be on the `Elements` tab. Switch to the `Network` tab.

![https://i.gyazo.com/1cb06f79cffb89b1f466d4802c5822bb.png](https://i.gyazo.com/1cb06f79cffb89b1f466d4802c5822bb.png)

-------------------------------------------

### **Step 2: Refresh your page**

After your page has finished refreshing, select the `Profile` request. Oh, the confusion. Yes, there's two. I tend to select the lower one on the list, this usually tends to be the correct one. Make sure you're on the `Fetch/XHR` filter to locate it quickly.

![https://i.gyazo.com/8e1109642fa98adb1a93a9512ed7d81f.png](https://i.gyazo.com/8e1109642fa98adb1a93a9512ed7d81f.png)

-------------------------------------------

### **Step 3: Fetch your `auth token`**

You'll know if it's the correct `Profile` request if you can locate your `auth token` in it. Under `request headers` you will find your `auth token`. Make sure NOT to copy the `bearer` part of the `auth token`. Also make sure to keep it private as this gives anyone access to your account with the right tools.

![https://i.gyazo.com/73cc87a4487228cc497fac0ee6f3ddb3.png](https://i.gyazo.com/73cc87a4487228cc497fac0ee6f3ddb3.png)

### **Step 4: Launch the sniper**

Open the `accounts.txt` file in the folder you made earlier. Copy your `auth token` and add `:bearer` after it. Yes, include the colon (`:`). Save and close the notepad. You're now ready to open the sniper; double-click the `.exe` and input the name you want to snipe!

-------------------------------------------

# **V. Conclusion**

You're now ready to attempt sniping names! But oh, what do you put for the `offset`? For now, you could put `0`. If you do want to learn how to effectively use `offset`, check out sections `VIII` and `IX` in my comprehensive `Beginner's Sniping Guide` found [here](https://github.com/NameMC/BASIC-SNIPING-GUIDE).

Have an amazing day!

## - FAQs -

> This is here in case you had any questions... there are likely answers

```sh
Does the sniper steal my account?! How do I know if it's safe?
```
You can download the source code [right on the Github repository](https://github.com/Kqzz/MCsniperGO). You can skim through it and clearly see that it doesn't compromise your account's security. If you don't trust it regardless of that, just don't use the sniper.

```sh
Why does it say my account could not be authenticated?
```
Several reasons... actually.
You could've put in the `auth token` incorrectly. Did you accidentally include the `bearer` part? Or did you forget to add `:bearer` after? **Important**: Your `auth token` expires after 24 hours. You'll have to fetch a new one each day you snipe and follow the same steps in section `IV`.

```sh
How did someone beat me!! I'm using the bot and I didn't get the name!!
```
You won't get your dream name first try. To be completely honest, expect *lots* of failure. Sniping is mostly luck + the amount of accounts you use. Most big snipers use 50+ accounts, so your chances are slim. That's not to say "don't try", though. Again, if you want to seriously get into sniping, check out [my guide](https://github.com/NameMC/BASIC-SNIPING-GUIDE).

```sh
I want the name "Dog" but it won't let me have it! 
```
This is a name *sniper*, not name *getter*. What I mean is the program attempts to claim *dropping* usernames which can be found on [NameMC](https://namemc.com/minecraft-names) or if you like 3-character names specifically, on [3NAME](https://3name.xyz/list).
