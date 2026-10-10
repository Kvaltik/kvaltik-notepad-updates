# Kvaltík Notepad — aktualizace 📱💻

Tento **veřejný repozitář je určený pouze pro distribuci aktualizací** aplikace Kvaltík Notepad pro Windows a Android. Zdrojový kód aplikace zůstává uložený samostatně v soukromém repozitáři.

## Stáhnout aplikaci

➡️ **[Všechny vydané verze (Releases)](https://github.com/Kvaltik/kvaltik-notepad-updates/releases)**

Každé vydání aplikace má obsahovat:
- **`KvaltikNotepad-Android.apk`** — instalace pro Android.
- **`KvaltikNotepad-Setup.exe`** — instalátor pro Windows.

Pokud zatím v Releases nic není, distribuce se ještě připravuje a uvedené instalátory tu zatím nejsou dostupné.

## Jak fungují automatické aktualizace

Od verze **1.1.0** aplikace při spuštění kontroluje poslední veřejné vydání. Pokud najde novější verzi, nabídne dialog **Aktualizovat / Později** s popisem změn.

- **Později** — pokračuješ v práci, oznámení se ukáže při příštím spuštění.
- **Aktualizovat** — otevře odkaz ke stažení příslušného instalátoru z GitHub Releases. Instalaci potvrdíš v systému.
- Aplikace umožňuje aktualizace ověřit také ručně.

Poznámka: tento kanál nesynchronizuje uživatelské poznámky; jde pouze o vydávání nových verzí aplikace.

## Bezpečnost

Tento repozitář **neobsahuje hesla, zdrojové kódy, tokeny ani poznámky uživatelů**.
Vydání budou zveřejněna až po sestavení a nastavení bezpečného podepisování aplikací.

**Upozornění pro Android:** APK instalovanou s jiným podpisovým klíčem nejde aktualizovat přímo. Před případnou přeinstalací staré verze zálohuj poznámky — odinstalace může vymazat lokální data.
