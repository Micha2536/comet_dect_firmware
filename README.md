:warning:Hinweis:warning:
Das einspielen einer Firmware erfolgt auf Eigenverantwortung. Meckert nicht rum, wenns mal schief geht :wink:
Beachtet die txt-Datei mit den MD5-Prüfsummen, um die Integrität der entsprechenden Firmwaredatei zu prüfen.

Vorgehensweise um die Firmware zu übertragen

Umbenennen der Originaldatei 06.04.03.xx.avm.de.upd…

… bei einer Originalbox von AVM in
dect-06.04-avm-de-049.image

… bei der 1und1 Version in
dect-06.04-1und1-de-049.image

… bei der internationalen Variante in
dect-06.04-avme-de-04x.image
x = Ländercode (z.B. 3 für Österreich)

Diese Datei dann auf einen an der Fritzbox angeschlossenen USB-Stick mit FAT32 ins Hauptverzeichnis kopieren. Box neustarten und dann sollte der Comet Thermostat die Firmware finden.

Edit :
26.07.21 / 21:50

txt-Datei mit allen MD5 Prüfsummen hinzugefügt
Changelog der Comet Firmware hinzugefügt
zip Archiv aktualisiert
Archiv entpackt, falls jemand nur eine Version braucht
Detailinformationen zu den Versionen

Version 3.68
· Test: einige wenige Geräte melden sich nicht mehr regelmäßig bei der Box

Version 3.66
· Behoben: Optimierte Ventilsteuerung zur Vermeidung von Adaptierungen im Betrieb
· Behoben: Gelegentlich zu lange Basissuche

Version 3.65
· Behoben: Optimierte Ventilsteuerung zur Vermeidung von Adaptierungen im Betrieb ohne Updateprobleme

Version 3.64
· Test: Ventilsteuerung aus 3.62 zum Testen

Version 3.63
· Test: Ventilsteuerung aus 3.61 zum Testen
· Behoben: Probleme bei Update über Repeater seit 3.61

Version 3.62
· Behoben: Optimierte Ventilsteuerung zur Vermeidung von Adaptierungen im Betrieb

Version 3.61
· Behoben: Gelegentlich zu lange Basissuche

Version 3.60
· Behoben: Neue Ventilsteuerung vermeidet Adaptierungen im Betrieb

Version 3.54
· Neu: Unterstützung für die Urlaubsschaltung
· Behoben: Fehlerhafte Anzeige der IPEI im Heizkörperregler-Display

Version 3.53
· Neu: Unterstützung für Urlaubsschaltung

Version 3.51
· Behoben: Verbindungsaufbau für Managementverbindungen (Anmelden/abmelden/Locate) mit Wiederholungen

Version 3.50
· First Release

