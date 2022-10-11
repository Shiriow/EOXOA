# EOXOA

# **[Download](https://github.com/Shiriow/EOXOA/releases/latest)**


Full Changelog: https://github.com/Shiriow/EOXOA/wiki

Skillsim: https://shiriow.github.io/overhaul/eox/

TildeHat's Class Addition Mod: https://github.com/Tildehat/EON-Class-Addition-Mod

---

# **Installation:**

If you’re continuing from a vanilla playthrough then rest your party members

**Luma:**

Drag and drop into the “luma/titles/00040000001D4E00” folder (or create them if they dont exist) in your SD card and rename codeNA.ips to code.ips 

(luma/titles/00040000001D5200 folder, and codeEU.ips to code.ips for EU region)

**For Citra:**

1: Download Citra Nightly/Canary https://github.com/citra-emu/citra-nightly/releases

2: Right click EOX -> Open Mods Folder

3: Place the romfs folder and rename your version’s .ips to code.ips


**Uninstall:**

Remove the added folders and files, don't forget to rest your party members

---

You can contact me on Discord: Shiri#7034, or find me in the [r/EtrianOdyssey Discord Server](https://discord.com/invite/8jsCx6F)


All Overhauled classes have their level gates removed


**Bugs:**

Getting Shadowstrike and Sylphid to activate with the same character will crash the game.

---

Includes some Optional files which adds a multiplier to enemy stats, and others that removes Buccaneer and Alchemist level gates (just dont forget these classes are designed around having them)



Overwrite enemydata.tbl in romfs/Monster/Table/

**enemydata x1.13.tbl:** just multiples the 6 stats by 1.13x

**enemydata x1.15 non agi.tbl:** doesn't touch AGI as increased enemy AGI also makes blinsides more frequent

**enemydata xvarious.tbl:** x1.2    Str  Luc  Int     ; x1.3    Vit  Wis  ; x1.1    Agi       

**enemydata progress.tbl:** 

Randoms's modifier for the 6 stats and MaxHP increases as you get to new stratums: starts at 1.05x for S1, 1.07x S2, x1.1 S3, etc. Caps at 1.25x on S9 with AGI capping at x1.1 at S3; 

FOEs are x1.25 STAT+HP, x1.1 AGI from the start; Bosses are similar but with no HP multiplier    
