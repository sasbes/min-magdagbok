# Min magdagbok

Detta är en offline-förberedd webbapp (PWA) för Android.

## Funktioner
- Registrering av toalettbesök
- Bristol-skalan typ 1–7
- Mängd, symptom, blod, smärta, trängning och anteckningar
- Kalender och dagvy
- Statistik över Bristol-typer och symptom
- Lokal lagring i webbläsaren
- Export/import av säkerhetskopia i JSON
- Service worker för offline-användning efter första laddning

## Installera på Android
PWA-installation kräver att appen publiceras via en HTTPS-adress (eller körs lokalt via localhost).
1. Lägg upp filerna på en HTTPS-webbserver, till exempel GitHub Pages eller annan webbhost.
2. Öppna adressen i Chrome på Android.
3. Öppna Chrome-menyn och välj "Installera app" eller "Lägg till på startskärmen".

Detta paket är inte en färdig APK-fil. Det är en installerbar webbapp som kan läggas på hemskärmen och köras fristående.
Uppgifterna sparas lokalt på enheten och delas inte automatiskt med någon server. Rensa inte webbläsardata utan att först exportera en säkerhetskopia.
