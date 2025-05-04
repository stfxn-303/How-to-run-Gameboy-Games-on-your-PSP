# How-to-run-Gameboy-Games-on-your-PSP
A guide on Gameboy Advanced Emulation on PSPs for complete beginners


⚠️ So you’ve already modded your PSP-3000 (good job 👍), and now you’re ready to jump into some Game Boy Advance nostalgia — *Pokemon FireRed*, *Metroid Fusion*, *Golden Sun*, you name it.
And if you haven't modded your PSP-3000 with Custom Firmware installed-don't worry, i've made  a guide on that too, check [this](https://github.com/stfxn-303/Beginners-Guide-to-Modding-PSP3000)  out first and come back once you've figured it out: 


This guide walks you through getting **TempGBA** up and running — it's a lightweight emulator that works great on modded PSPs.


---

## 📦 What You’ll Need

- Your modded PSP-3000
- A memory stick (4GB+ recommended) or an SD card with a Pro Duo Adapter
- USB cable or card reader
- A Windows/Mac/Linux PC
- [TempGBA emulator]
- Your favorite GBA ROMs (we tested with *Pokemon FireRed.gba*)

---

## 🛠️ Step 1: Download and Extract TempGBA

1. There are many versions of TempGBA circulating the internet, each version altered by different programmers, unfortunately i won't be able to directly link a trusted download page in this guide since you'll never know if the link gets out dated and i can't hold liability to what happens if you download the wrong emulator , but with a little bit of going around and researching under popular reddits and other github repositories, i'm sure you can find a trustworthy version. However, i will add TempGBA version r162 here in the repository, i went around in so many different sites to find a working, safe version that i lost track of where exactly i found it.


2. Extract the `.zip` — you should get a folder named `TempGBA` with `EBOOT.PBP` inside.

---

## 📁 Step 2: Transfer TempGBA to PSP

1. Plug your PSP into your PC using a USB cable.
2. On your PSP, go to **Settings > USB Connection**.
3. On your PC, open the PSP’s memory stick and navigate to:

```
PSP/GAME/ 
```

4. Drop the entire `TempGBA` folder into that `GAME` directory.

After that, it should look like this:

``` PSP/GAME/TempGBA/EBOOT.PBP ```


---

## 🎮 Step 3: Add GBA Games (ROMs)

1. Inside the `TempGBA` folder, create a folder called `roms` (if it’s not already there).
2. Place your `.gba` files inside that folder, some trusted sites to download roms from are [Emugames](https://www.emugames.net/) , [Romsfun](https://romsfun.com/) , and [Emulator Games](https://www.emulatorgames.net/) , for example:

```
PSP/GAME/TempGBA/roms/Pokemon FireRed.gba
```
When you download stuff from the internet, they often come in zip files, 7z files, torrents, and many other kinds of compressed forms, you have to make sure that the folder structure looks exactly like this and there are no other folders seperating them, they're besties andd don't work unless they're all close together. for example, if your folder structure looks a little something like:

```
PSP/GAME/folder/TempGBA/roms/folder/Pokemon FireRed.gba
```
it will not work, there can be no folders seperating them. 

## 🚀 Step 4: Launch TempGBA

1. Disconnect USB and go back to the PSP home screen, make sure you safely eject it from your computer or else it might corrupt the data in your memory stick/SD card
2. Go to **Game > Memory Stick**, and you should see something like **TempGBA**
3. Launch it.
4. You’ll see a list of your `.gba` games. Select one and press **O** to start playing!


---

## 🎯 In-Game Controls & Features

- Press **The playstation button of your console** while in-game to bring up the emulator menu.
- You can:
- Save and load already saved states
- Adjust screen size & aspect ratio
- Change frameskip settings for smoother gameplay
- Remap controls if needed

**Bonus tip: if you don't like how the game's resolution makes it look so tiny in the screen of your PSP, click the button on your PSP that has a Playstation icon-this will lead you to the TempGBA menu, where you save your game states and load already saved game states, click display mode and switch to "USER GU" , set maginification from somewhere around 150% to 190%, do note that setting it too high will cost your game's interface to crop out**

---

## ❓Troubleshooting

**Q: My games aren’t showing up in TempGBA.**  
➡️ Make sure the `.gba` files are inside the `roms` folder under `TempGBA`, there are also moments where your .gba file is a corrupted copy and when that happens it won't run too, if you tried all the different things you can think of and you still get messages like "failed to load game" with black screens, consider redownloading the .gba file from a different site from the ones i've mentioned or any other trust worthy website that you found when researching!

**Q: The game is slow or laggy.**  
➡️ Use the emulator menu (**Playstation Button**) and increase frameskip.

**Q: Can I use cheats?**  
➡️ TempGBA doesn’t support cheat codes natively, but you can try patching the ROM beforehand using tools on PC.

---
## 🧃 That’s It!

You’re now ready to relive the golden age of GBA gaming — on a sleek little PSP. Whether you’re doing a Nuzlocke in *FireRed*, speedrunning *Mario & Luigi*, or finally finishing *Minish Cap*… it all works like a charm.

If this guide helped, give it a ⭐ or share it with someone else stuck in 2005 (in a good way).

---

> Made by fans, for fans.  
> Tested with: PSP-3006 running PRO-C2 CFW, TempGBA r162, *Pokemon FireRed.gba*.

## 🔍 About Author
Woah you scrolled down all the way here? I'm so happy my tutorial became so useful to you! i'm just a humble 17 year old script kiddie who has nostalgia for an era he wasn't even born in,

