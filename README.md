# Magic Mouse 2 Scrolling on Windows 10

## General Notes
* There are a couple paid programs out there that will get scrolling working for your magic mouse. The most popular one asks you to buy a _subscription_ license. **No thanks**.
* There are some tutorials that suggest downloading Apple BootCamp drivers from the Apple support site. This will **not** work for the Magic Mouse 2.

## Steps
1. Install [7-Zip](https://www.7-zip.org/a/7z1900-x64.exe).
2. Download [Brigadier](https://github.com/timsutton/brigadier/releases) from GitHub.
3. Extract brigadier.exe from the ZIP archive.
4. Press the Windows key and type Command Prompt, then run it.
5. Navigate to the folder where Brigadier was extracted:
    * If you downloaded brigadier to your "Downloads" folder you may type: `cd %USERPROFILE%\Downloads`
    * Press `<enter>`
    * If brigadier downloaded to a different path, you will need to use that instead.
6. Run brigadier:
    * Type: `brigadier.exe -m MacBookPro14,1`
    * Press `<enter>`
7. Brigadier will now download the Bootcamp support software from Apple. The entire thing can take 5 minutes.
8. Now, in Explorer, navigate to the folder where the support software was downloaded to. It should be in the same folder as Brigadier.
9. Run BootCamp-041-89042\BootCamp\Drivers\Apple\AppleWirelessMouse64.exe
10. Done!

**This method is _not_ the same as downloading the BootCamp support software directly from the Apple Support website. If you do that, scrolling will _only_ work with the Magic Mouse 1.**

## References
* [Paid Solution](https://apple.stackexchange.com/questions/335276/apple-magic-mouse-2-not-scrolling-magic-mouse-1-works-windows-10-pc)
* [Solution that only works for Magic Mouse 1](https://discussions.apple.com/thread/8521118)
* [Best solution (this one)](https://discussions.apple.com/thread/250016700)
* [Easiest solution (untrusted?)](https://github.com/Rain9333/MagicMouse2DriversWin10x64)

The "Easiest solution" provides an easy way to download the software you need to run in step 9, allowing you to skip all other steps. It is usually best to get the software from the source, however.
