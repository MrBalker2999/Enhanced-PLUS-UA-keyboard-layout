# Ukrainian (extended) layout for Windows OS.
This extended layout includes Russian characters with their standard location in the Russian layout, and also fixes the shortcoming of the standard extended Ukrainian layout, due to which the capital "г" is not written with *CapsLock* pressed.
Designed for people who have switched or are switching to the Ukrainian language, but have a long-standing past, semi-conservative people who simply cannot move away from using Russian or Internet trolls.

## HOW TO USE
When pressing the right *Alt* and the key of certain letters, a Russian letter will be written.
If you also press *Shift* at the same time --- a capital letter is printed. Toggling *CapsLock* also works.

## HOW TO USE IN DETAIL
[Button] -- [Result with right *Alt* pressed]
и -- ы
ъ -- ъ
ё -- е
' -- ё
г - г (reminder)

## GETTING STARTED
Tested on Windows 11. Instructions will also be for it. On older systems for Windows 10, testing has not been conducted and work is not guaranteed.

## COMPATIBILITY CHECK
__Check even if you have Windows 11.__ Go to the standard (system) Windows settings -> System -> About the system. In the "Device specifications" section, expand to "System type".
64-bit operating system, processor based on __ARM__ architecture --- __WON'T WORK!!!__

[System Type] -- [Installation File Name]
_64-bit operating system, processor based on x64 architecture_ -- __UA-ru_amd64.msi__
_32-bit operating system, processor based on x64 architecture_ -- __UA-ru_i386.msi__
_32-bit operating system, processor based on x32 architecture_ -- __UA-ru_i386.msi__

## INSTALLATION
1) Run the required file (described a little above);
2) Wait for the window to appear with a message about successful installation (it may take some time);
3) Click "Close";
4) __MUST__ restart the computer.
5) Go to the standard (system) settings Windows -> Time and language -> Language and region -> three dots next to Ukrainian -> Language options -> three dots "Ukrainian (extended)" -> Delete).

## QUESTIONS
* *How to delete?*
1) Run the file used for installation (if you don't remember which one, read the "Compatibility check" section above);
2) Select "Delete keyboard layout";
3) Click the "Done" button;
4) Go to the standard (system) settings Windows -> Time and language -> Language and region -> three dots next to Ukrainian -> Language options -> three dots "Ukr. (extended) with Russian letters and full г" -> Delete);
5) Restart the computer.

* *Why do I need this keyboard?*
If your preferred language is Ukrainian, you are switching to one less extra language.
For example, you don't really need to switch between THREE (English, Ukrainian, Russian).

* *The installation instructions say to remove "Ukrainian (extended)". Is it safe?*
Yes, absolutely. You are not removing the language, but only the keyboard (layout).

* *After updating Windows, I have the standard layout again. What should I do?*
This is how Windows works and, unfortunately, I cannot fix it at the moment. There are 2 solutions here and both are police.
1) Restart your computer. This is still a real option.
2) Go to the standard (system) Windows settings -> Time and language -> Language and region -> ellipsis next to Ukrainian -> Language options -> Add a keyboard -> "Ukrainian" (you will probably need to add the same one, not the extended one) -> ellipsis next to "Ukrainian" (yes, this is the one that was installed as much as possible) -> Delete.

* *The name has "amd", but I have an Intel processor. Will this work on my computer?*

Yes, it will work. Look at the name in more detail. amd64 is: 64-bit x86 architecture created by AMD, fully compatible with Intel 64. That is, it will work on Ryzen, Intel Core, and even Xeon. In Windows, this is the traditional connection as: x64, x86-64, amd64. It's the same thing.

### Author
Vladyslav L.

Contact:
Twitter (X): [Vladyslav](https://x.com/MrBalker_2999) --- write with any questions or complaints.

### Version History
* 1
* Release

### Licenses
The project is licensed under the MIT license. Read more in *LICENSE.md*.
