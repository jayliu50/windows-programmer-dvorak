windows-programmer-dvorak
=========================
About
-----
Forked from [jayliu50/windows-programmer-dvorak](https://github.com/jayliu50/windows-programmer-dvorak). 

**Dvorak** is a keyboard layout that makes typing easier and lets you type 
faster. **Programmer Dvorak** is a variant of Dvorak with different number and 
symbol positions to help you write programs more efficiently. 

This layout is based on Programmer Dvorak, but swaps `Caps Lock` and 
`Backspace` (similar to Colemak) because `Backspace` is used more frequently and 
should be closer to home row. This layout also switches to Qwerty when holding 
`Ctrl` or `Win` so keyboard shortcuts are easier to use, similar to 
"dvorak-qwerty command" on mac.

Layout
------
Keep in mind that `Caps Lock` and `Backspace` are swapped.

![Programmer Dvorak layout](https://user-images.githubusercontent.com/56197853/116783257-13d90600-aa8e-11eb-83b2-277b385cde4e.png)

By Etatoby - This file was derived from:  KB United States Dvorak.svg, GFDL, 
https://commons.wikimedia.org/w/index.php?curid=88699716

Installation
------------
1. Go to 
[releases](https://github.com/glibg10b/windows-programmer-dvorak/releases).
2. Click on `usprogdv.zip` and download it.
3. Go to your Downloads folder.
4. Right-click `usprogdv.zip` -> `Extract All...`.
5. Open the folder after extracting.
6. Run `setup.exe`.

How to use
----------
Press `Ctrl` + `Shift` to switch between your current keyboard layout and 
Programmer Dvorak. If that doesn't work, press `Alt` + `Shift` until 
`English (United States)` is highlighted, then press `Ctrl` + `Shift`. Click 
[here](https://winaero.com/change-hotkeys-switch-keyboard-layout-windows-10/) to 
learn how to change these keyboard shortcuts.

Uninstallation
--------------
1. Press `Windows Key` + `I` to open Windows Settings.
2. Click on Apps.
3. Scroll down to "United States-Dvorak - Programmer" and click on it.
4. Uninstall.

Compiling it yourself
---------------------
1. Download `programmers-dvorak.klc`.
2. Download Microsoft Keyboard Layout Creator from 
[here](https://www.microsoft.com/en-us/download/confirmation.aspx?id=102134).
3. Go to `C:\Program Files (x86)\Microsoft Keyboard Layout Creator 1.4\`.
4. Backup `kbd.h`.
5. Open `kbd.h`.
6. Go to the following line:
```
#define T0E _EQ(                           BACK                      )
```
7. Replace `BACK` with `CAPITAL`.
8. Go to the following line:
```
#define T3A _EQ(                           CAPITAL                   )
```
9. Replace `CAPITAL` with `BACK`.
11. Open Microsoft Keyboard Layout Creator.
12. Click `File` -> `Load Source File...` and choose `programmers-dvorak.klc`.
13. Click `Project` -> `Build DLL and Setup Package`.

Tips
----
- If you've made changes to they layout but they didn't seem to apply, restart
your PC.
- Check [this](http://www.dvzine.org/) comic, you'll enjoy it and you'll learn a 
lot about the history of Dvorak and Qwerty
- Don't rearrange the keys on your keyboard, you're not supposed to look at them
anyway. Besides, no one but you will be able to use your computer ;)
- If you want to learn Programmer Dvorak, I suggest using 
[Ratatype](https://www.ratatype.com/courses/english-dvorak/) to learn Dvorak and 
[TODO](https://programmer-dvorak.appspot.com/) to learn Programmer Dvorak. Try 
to get 3 stars per lesson on Ratatype, otherwise you'll struggle later on. Stop 
when you reach Lesson 12. Continue at appspot on Lesson 30 and do all of the 
rest of the lessons there. Once you finish, continue at Lesson 12 on Ratatype.