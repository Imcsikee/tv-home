# TV Home – Windows-telepítő

[**A teljes Windows-csomag letöltése (ZIP, kb. 13 MB)**](https://github.com/Imcsikee/tv-home/raw/refs/heads/downloads/tv-home-windows-20261026/tv-home-windows-visszaallithato.zip)

A csomag a projekt változatlan forrásából fordított APK-t, a Google hivatalos Windows Platform Tools eszközeit, telepítőt, visszaállítót és a licenceket tartalmazza.

1. A Windows gép legyen a tévével azonos hálózaton.
2. Töltsd le és csomagold ki a teljes ZIP-et.
3. A tévén nyomd meg a Home gombot, majd Windows alatt indítsd az `INSTALL.cmd` fájlt.
4. A tévén fogadd el az ADB-hibakeresési engedélykérést, ha megjelenik.

A beállított cím `192.168.0.4:5555`. Android 11 vagy újabb szükséges. A telepítő leáll, ha nem tudja menteni és ellenőrizni az eredeti kezdőképernyő beállítását. Gyári alkalmazást nem töröl, nem tilt le, és alkalmazásadatot nem ürít.

## Az eredeti kezdőképernyő visszaállítása

Indítsd a `RESTORE.cmd` fájlt ugyanabból a kicsomagolt mappából. Tartsd meg a teljes mappát, különösen a telepítéskor létrejövő `backup` mappát és `last-backup.txt` fájlt.

A gyári kezdőképernyő alkalmazása és adatai megmaradnak; a visszaállító az eredeti alapértelmezett HOME-tevékenységet választja ki újra, és ellenőrzi a beállítást. Ez nem teljes firmware- vagy alkalmazásadat-mentés. A csomag a letöltéskor még nem tartalmazza a tévé mentését: azt a helyi Windows-telepítő készíti el.

Az APK fordítása, aláírása, igazítása, a ZIP integritása és a hivatalos ADB-archívum ellenőrzőösszege ellenőrizve lett. A Windows-szkriptek és a tényleges tévés telepítés/visszaállítás futtatása még nincs tesztelve.

SHA-256 (`tv-home-windows-visszaallithato.zip`):

```text
1c248a9d134fc6d63ae2bfe85759e5ac62b231640fe580ab57a41e3a4662169f
```

Ez az ág a letölthető csomagot tartalmazza.
