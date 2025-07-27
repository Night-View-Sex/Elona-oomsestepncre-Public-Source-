**Original Description:**  
This is a Nasuko-flavored variant of SEST.

It has the following development principles:
- To allow modularity between NC and SEST with as little conflicts as possible;
- Add more romantic and roleplaying elements, and;
- Add an endgame for 廃人(haijin) players.

(We will focus on cTalk related elements, postgame features, and features to improve convenience, while not going too deeply into elements that can be adapted to all play styles and that would drastically change the game balance until the story is cleared.)  
(It should be as considerate as possible to the providers of materials up to SEST.)

Eggplants! I want to eat eggplants! Words of Aoi Nasuko.

**Re:**  
We aim to add more English compatibility with NC, and more roleplaying and customization features.  
Note: This may take some inspiration from certain Plus mechanics.

## About the Repo
Sorry, the files are compressed. I'm in mobile and can't upload in masse.

- NVS

## Installation

1. Refer to this guide from the [Omake Family Variant Wiki](https://web.archive.org/web/20240623183744/http://elona-omakefamily-wiki.com/?%E5%B0%8E%E5%85%A5%E6%96%B9%E6%B3%95) for steps on how to install OOMSEST, or;
2. Download the attached Pre-pack from [here](https://mega.nz/file/2gcmwIib#RP0OwY_WxlczD6rqk6WjeuUshQ7aykHukHGtEaLDyhQ). Extract it to `elona_oomsestepnc`.
3. Extract the contents of this repository's latest archive to the `elona_oomsestepnc` folder, overwriting all existing files.
4. Run `oomSESTep_NC.exe`.

## Building

1. Download a copy of this repository, and extract. You may also want to keep a fresh install of OOMSESTEPNC in handy.
2. Download the HSP3.6 SDK (`hsp36.zip`) from [here](http://hsp.tv/make/downlist.html) or from OpenHSP for the EN version [here](https://github.com/onitama/OpenHSP/releases) and extract it somewhere.
3. Download `longint.lzh` [here](https://www.vector.co.jp/download/file/win95/prog/fh403730.html).
4. Extract with an archive extractor such as Winrar or 7zip (making sure to set the proper Name Encoding before you extract all files).
5. Copy the `longint.hsp` file from the `longint.lzh` archive to the `src` folder. Otherwise, you will get an error telling you about missing `.hsp` files not included in this repository.
6. Open `src/main.hsp` with `hsed3.exe` from the HSP3.6 SDK folder. Press <kbd>F5</kbd> to compile and run under debug mode.
7. Press <kbd>Ctrl+F9</kbd> to create an executable named `oomSESTep_NC.exe`. You can then copy it to your `elona_oomsestepnc` install folder.

**Warning**: If you make any changes to the code, *always make sure the file encoding is set to SHIFT_JIS* to avoid crucial issues!

## Thanks

The Omake Family Tree:
- Omake Oniichan, for starting the Omake variants, upon which ALL of this is built from;
- Seacolor, for Omake Overhaul, which [exists and is in development](https://misskey.seacolorswind.com) to this day.
- ENHack Team, for making Omake Overhaul viable for English users (Doorknob, KI_Foobar, kusotools)
- SEST Team, also for making South Tyris a location we could visit ingame as well as adding an expanded endgame.
- Aoi_Nasuko, for this wonderful variant and doing all he can to maintain language parity for both communities.
- And the now-unknown developers for OOM and OOMSE, which if you know of their names, you may let us know to amend this.

Misifu, for the pre-pack efforts which allowed for easy access to the entire game at least for the English side of the community,
Mizucchi, for help with some codes and inspiration from his 'Mizucchi/Mini Fix' edits.

JianmengYu for providing crucial advice on how to edit the variants and read HSP,

Everyone else who contributed to the Omake Family Tree and NC in some way.
 - Doorknob
 - Nonbirithm
 - Anon(s) from the ノースーチィリス server and /jp/ 
 - And others.

f1r3fly, Sunstrike, Schmidt, and Elvenspirit, for contributing to Elona's original English translation.

Noa, for creating the game that has brainrotted many over the course of decades.

And *you*, dear reader.
