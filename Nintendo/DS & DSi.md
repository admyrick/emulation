- [DeSmuME](https://github.com/TASEmulators/desmume)
- [melonDS](https://github.com/melonDS-emu/melonDS)
  - [melonDS Nightly](https://github.com/rafaelvcaetano/melonDS-android/releases/tag/nightly-release)
  - [melonDS-Android](https://github.com/rafaelvcaetano/melonDS-android)
- [NooDS](https://github.com/Hydr8gon/NooDS)
- [iNDS](https://github.com/iNDS-Team/iNDS)

---

- [How to play DS games in HD Widescreen](https://gbatemp.net/threads/how-to-play-nds-games-in-hd-widescreen-16-9-21-9-32-9.538988/)
  - The "cheat" code is overwriting part of the game to say render in 16x9. Then the settings in drastic need to full screen the generated image. If you want to make it a different ratio then you will need to create new codes. To do this you can take one of the generated codes and replace 1C72 with one of the following:

    - 16:9 - 0x1C72
    - 16:10 - 0x199A
    - 18:9/2:1 - 0x2000
    - 21:9 - 0x2555
    - 32:9 - 0x38E4
