AccessVision App
Flutter-appen är användargränssnittet för AccessVision. Den används för att hantera registreringsnummer, se notiser, visa kameraflöde och skicka kommandon till grindstyrningen.

Funktioner
- Visa och hantera registreringsnummer.
- Ange status Godkänd eller Ej Godkänd.
- Visa notiser och senaste händelser.
- Ta emot realtidsuppdateringar via WebSocket.
- Visa livekameraflöde från Raspberry Pi.
- Skicka manuella kommandon för att öppna eller stänga grinden.

Teknik
- Flutter
- Dart
- Dio för HTTP-anrop
- WebSocket för realtidskommunikation

Kom igång
1. Installera Flutter SDK och en kompatibel utvecklingsmiljö.
2. Öppna appens projektmapp.
3. Hämta paketen:
   flutter pub get
4. Kontrollera API-adresser och portar i appens konfiguration/serviceklass.
5. Starta appen:
   flutter run

Konfiguration
Kontrollera att backendens och Raspberry Pi-delens adresser är korrekta för din miljö. Undvik att hårdkoda produktionsadresser och hemligheter.
Felsökning
- Kontrollera att API-servern är tillgänglig från telefonen.
- Kontrollera HTTP- och WebSocket-adresser samt portar.
- Kontrollera Androids nätverks- och notisbehörigheter.
- Kontrollera att Raspberry Pi-strömmen är igång om livebilden saknas.
