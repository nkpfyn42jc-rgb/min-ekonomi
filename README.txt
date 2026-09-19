# Min ekonomi

Detta är en iPhone-anpassad PWA-prototyp.

## Funktioner i version 1
- Översikt med pengar kvar per månad och ungefärlig daglig spend
- Diagram
- Transaktioner med manuell registrering, redigering genom borttagning och kategorier
- Budget per kategori
- Sparmål med målbelopp, datum och månadsbehov
- Separata konton/tillgångar för sparkonto och investeringar
- Lokal lagring via localStorage
- Offline-cache via service worker
- iPhone/PWA-manifest och ikon

## Installera på iPhone
1. Lägg filerna på en HTTPS-webbserver.
2. Öppna sidan i Safari på iPhone.
3. Välj Dela -> Lägg till på hemskärmen.
4. Öppna appen från hemskärmen.

## Viktigt om bankkoppling
Varbergs Sparbank anger att licensierade tredjepartsaktörer kan använda bankens PSD2/Open Banking-APIer med kundens medgivande. En riktig bankkoppling kräver därför en säker backend och en licensierad Open Banking-leverantör eller motsvarande bankavtal. Denna prototyp skickar inga bankuppgifter.

Face ID: en webbapp kan senare använda WebAuthn/passkeys, vilket på kompatibla iPhone-enheter kan använda Face ID som enhetens biometriska verifiering. Det kräver HTTPS och en riktig webbdomän.
