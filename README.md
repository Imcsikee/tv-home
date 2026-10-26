# TV Home – Windows letöltések

## Javítás 1.0.1: óriási YouTube-csempe

[**A javított Windows-frissítőcsomag letöltése (ZIP, kb. 13 MB)**](https://github.com/Imcsikee/tv-home/raw/refs/heads/downloads/tv-home-windows-20261026/tv-home-windows-fix-1.0.1.zip)

Ha csak egy vagy két kedvenc alkalmazás volt telepítve, a dokkoló túlméretezte a csempéket. Az 1.0.1 verzió legalább öt helyre méretezi a kedvenceket, így egyetlen YouTube-csempe sem foglalja el az egész sávot.

1. A frissítő ZIP-et külön új mappába csomagold ki.
2. A Windows gép legyen a tévével azonos hálózaton.
3. Indítsd az **UPDATE.cmd** fájlt. Most nem az INSTALL.cmd kell.
4. Ha a tévé engedélyt kér, fogadd el.

A frissítő a meglévő appot frissíti ugyanazzal az aláírással. Nem módosítja az alapértelmezett Home-ot, és nem írja át a korábbi telepítőmappában található mentést. Nem töröl vagy tilt le gyári alkalmazásokat. A cím továbbra is `192.168.0.4:5555`. Android 11+ szükséges.

**Tartsd meg a RÉGI telepítőmappát!** Az eredeti tévéfelülethez annak a mappának a **RESTORE.cmd** fájljával tudsz visszatérni. A szükséges, tévéhez tartozó backup és last-backup.txt a régi mappában van, nem a friss letöltésben.

Ez a HOME-beállítás visszaállítása, nem teljes tévérendszer-mentés.

A frissítő Windows alatti futtatása és a konkrét tévés megjelenés nincs itt tesztelve. A fordítás, az APK aláírása/igazítása, az eredeti aláírással egyezés és a ZIP integritása ellenőrizve lett.

## Korábbi teljes telepítő

[Az eredeti Windows-telepítőcsomag](tv-home-windows-visszaallithato.zip) változatlanul megmaradt.

A forrásjavítás: [dock-sizing-fix.patch](dock-sizing-fix.patch).
