# SheetCinch
Cinch allows you to customize native Android UI seamlessly, without root or Shizuku.

## No root, no Shizuku — how does it work?
Cinch does not modify the UI on the OS level. Instead, it functionally replaces it.

Using Accessibility Services, Cinch is able to (1) **detect** when you've done something to trigger a native UI sheet, (2) take the content from *below* that sheet and broadcast it in real time *above* the sheet, effectively **disappearing** the native UI solution, and then (3) **display** your own custom UI in its absence! _Detect • Disappear • Display!_

Well, there's a little more to it than that, but that's the important stuff.

## Permissions, and "do I need ADB?"
Cinch requires `Accessibility Services` and `Display Over Other Apps`. I wish there were an easier way, but unfortunately these are the minimum permissions needed for the majority of Cinch's functionality.

ADB is **not** an absolute requirement. However, if you are able to use it just once, it can aid in the setup for some features. No embedded ADB server (like Shizuku) is required per UI instance or continuously whatsoever.

---

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

<div align="right">

[![CC BY 4.0][cc-by-image]][cc-by]

</div>

[cc-by]: https://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/ʟɪᴄᴇɴꜱᴇ-CC%20BY%204.0-FFFFFF?labelColor=000000
