# Ukrainian (enhanced+) layout for Windows
Enhanced-PLUS-UA is a custom Ukrainian keyboard layout for Windows, extended with additional symbols and optional Russian letters for occasional use, without affecting the primary Ukrainian layout.  

It includes:
- Russian characters in their standard positions, as in a regular Russian layout;
- fixes a long-standing issue in the standard Ukrainian (Enhanced) layout (capital "Ґ" now types correctly with *Caps Lock*);
- adds some symbols that are normally only available on the English layout.

### Who is this for?
For people who have switched or are switching to the Ukrainian language, but have a russified past, Internet trolls and anyone who will find this useful.

---

# GETTING STARTED
Tested on Windows 11. Instructions are also for it. Work on systems older than Windows 10 is not guaranteed.

### COMPATIBILITY CHECK
Go to the standard (system) Windows settings -> System -> About the system. In the "Device specifications" section, look at "System type".

| System type | File name for installation |
| --- | --- |
| _64-bit operating system, x64-based processor_ | UA-ru_amd64.msi |
| _32-bit operating system, x64-based processor_ | UA-ru_i386.msi |
| _32-bit operating system, x32-based processor_ | UA-ru_i386.msi |
| _64-bit operating system, **ARM**-based processor_ | __WON'T WORK!!!__ |

### LANGUAGE CHECK
If your system is in Ukrainian &mdash; you can skip this item.

Go to the standard (system) Windows settings -> Time and language -> Language and region.  
If Ukrainian is not in the list of languages:
1) Click the "Add language" button;
2) Find Ukrainian in the list and click the "Next" button at the bottom left;
3) Check the desired boxes and click the "Install" button.

## INSTALLATION
1) [Download the archive](https://github.com/MrBalker2999/Enhanced-PLUS-UA-keyboard-layout/releases) and unpack it;
1) Run the desired file (described a little higher);
2) Wait for the window with a message about successful installation to appear (it may take some time);
3) Click "Close";
4) ___NECESSARILY___ restart the computer.
5) _RECOMMENDED_ to go to the standard (system) Windows settings -> Time and language -> Language and region -> three dots next to Ukrainian -> Language options -> three dots next to "Ukrainian (advanced)" -> Delete).

---

## QUESTIONS
* *How to remove?*  
    1) Run the file that was used for installation (if you don't remember which one, read the "Compatibility Check" section above);
    2) Select "Remove the keyboard layout";
    3) Click the "Finish" button;
    4) Go to the standard (system) Windows settings -> Time and language -> Language and region -> ellipsis next to Ukrainian -> Language options -> ellipsis next to "Укр. (розширена) з рос. літерами та повноцінною ґ" or "Українська (розширена+) розкладка" (depends on version) -> Remove);
    5) Go to the standard (system) Windows settings -> Time and language -> Language and region -> ellipsis next to Ukrainian -> Programs -> Installed programs -> ellipsis next to "Укр. (розширена) з рос. літерами та повноцінною ґ" or "Українська (розширена+) розкладка" (depends on version) -> Remove);
    6) Restart the computer.

* *Why do __I__ need this keyboard?*  
If your preferred language is Ukrainian, you will switch to one language less, or maybe two.  
_Trilingual version (English, Ukrainian, russian) used for example._

* *A similar keyboard is already available online, why choose this one?*  
The keyboards I found did not work for me (OS Windows 11) and probably will not work for you.  
This one will work like a charm.

* *The installation instructions say to remove "Ukrainian (enhanced)". Is it safe?*  
Yes, absolutely. You are not removing the language, but only the keyboard (layout).

* *After updating Windows, I have the standard layout again. What should I do?*  
This is how Windows works and, unfortunately, I cannot fix it. There are 2 solutions here and both are crutches.
  - Restart your computer. Windows doesn't always clean up after an update.
  - If the previous option didn't help: go to the standard (system) Windows settings -> Time and Language -> Language and Region -> ellipsis next to Ukrainian -> Language Options -> Add a keyboard -> "Ukrainian" (you probably need to add it, not the enhanced one) -> ellipsis next to "Ukrainian" (yes, this is the one that was just installed) -> Delete.

* *The name of the installation file has "amd" in it, but I have an Intel processor. Will this work on my computer?*  
Yes, it will. amd64 is a 64-bit x86 architecture created by AMD, fully compatible with Intel 64. That is, it will work on Ryzen, Intel Core, and even Xeon. In Windows it is usually called x64, x86-64 or amd64. It is the same thing.

---

### Author
Vladyslav L.

Contact:
Twitter (X): [Vladyslav](https://x.com/MrBalker_2999) &mdash; write questions, suggestions, complaints.

### Version history
* 1.1
  * Moved _ё_
  * Added ~ ` # $ € ^ [ { } ] — – ± ≠ | < >
  * Inspired by the work [described here](https://r2u.org.ua/wiki/keyboard/UkrainianUnicode)
* 1.0
  * Added russian letters

### Licenses
The project is licensed under the MIT license. Read more in *LICENSE.md*.  
Created with _Microsoft Keyboard Layout Creator 1.4_.
