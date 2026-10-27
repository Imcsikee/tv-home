# TV Home 2.0 – natív funkciók, gyors felület

[**Windows-frissítő és visszaváltó letöltése (ZIP)**](https://github.com/Imcsikee/tv-home/raw/refs/heads/downloads/tv-home-windows-20261026/tv-home-2.0.0-native-fast.zip)

1. Csomagold ki külön új mappába.
2. A gép legyen a tévével azonos hálózaton.
3. Indítsd az **UPDATE.cmd** fájlt. A cím: `192.168.0.4:5555`.

A korábbi gyors natív dokk/csemperajzolás maradt. Új funkciók: távirányítós kedvencek, rendezés, elrejtés, háttérkép-galéria és QR-feltöltés, PC-képmappa, ambient, megjelenés, vezérlőközpont, időjárás, Spotify és telefonos Android-billentyűzet. A részletes használat az OLVASS-EL.txt és FUNKCIOK.md fájlban van.

Az UPDATE nem módosítja a Home-kiválasztást, nem töröl appadatot, nem tilt le gyári appot, és nem írja át a régi Windows-mentést.

## Visszaváltás

- **RETURN_TO_FAST.cmd:** visszatér a korábbi gyors, egyszerű 1.0.1 felülethez. Azonos csomagnév, aláírás és verziókód; nincs eltávolítás vagy adatürítés. Az UPDATE.cmd újra felteszi a 2.0-t.
- **Gyári tévéfelület:** a RÉGI telepítőmappádban lévő RESTORE.cmd, annak backup és last-backup.txt fájljaival. Tartsd meg a régi mappát!

Spotifyhoz/billentyűzethez az Androidban felhasználói engedélyezés és adott esetben újrapárosítás kell. A mellékelt PC-segédek Python 3-at használnak, pip nélkül.

## Ellenőrzés

20 Android/JVM- és 9 Python-teszt sikeres, 0 kihagyott. A dokk 1/2/5 csempével, 720p/1080p méretben, cache/fókusz, kedvencmentés, rendezés-visszavonás, Activity és ambient, valódi JPEG-feltöltés, PIN/telefonpárosítás és visszavonás, szerverleállás, PC-hashprotokoll és PKCE/state ellenőrizve. Mindkét APK aláírása és igazítása ellenőrizve, a korábbi APK-val azonos tanúsítvánnyal.

A fizikai Tesla tévén a 2.0 FPS/RAM, megjelenés, Android-jogosultságok és élő Spotify-fiók innen még nem tesztelt. A Windows CMD-k végrehajtása is a helyi gépen történik.

## Korábbi csomagok

- [1.0.1 gyors javítás](tv-home-windows-fix-1.0.1.zip)
- [Eredeti teljes telepítő](tv-home-windows-visszaallithato.zip)

SHA-256: `f4983d2e22d257c57fa5e1a6a2b004a08a62b3704ed8dbfaaaa122b5118b84a2`
