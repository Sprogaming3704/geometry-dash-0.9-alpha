[README.md](https://github.com/user-attachments/files/29677116/README.md)
# Geometry Dash PL — Electron App

## JAK ZBUDOWAĆ .EXE

### 1. Otwórz CMD jako Administrator
- Naciśnij Windows
- Wpisz `cmd`
- Kliknij prawym → "Uruchom jako administrator"

### 2. Przejdź do folderu i zainstaluj
```
cd "%USERPROFILE%\Desktop\gd-electron2"
npm install
```

### 3. Zbuduj .exe
```
set CSC_IDENTITY_AUTO_DISCOVERY=false
npm run build-win
```

### 4. Gotowe!
Plik `dist\GeometryDashPL.exe` — wyślij znajomym!

## Skróty w grze
- F11 = pełny ekran
- Escape = wyjście z pełnego ekranu
