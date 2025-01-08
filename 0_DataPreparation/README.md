# Selbst erstellte Variablen
## Konsum-bezogene Features
- Paycheck Effect: Bezieht sich auf den Effekt, dass Konsumverhalten nach Gehaltszahlungen ansteigt, wenn 90% der Firmen den Lohn in einem bestimmten Zeitraum auszahlen (27. eines Monats bis 5. des Folgemonats).

- Inflation Sensitivity: Klassifiziert Produkte je nach ihrer Empfindlichkeit gegenüber Inflation (hoch, mittel, niedrig). Produkte wie Brot sind stärker betroffen als z. B. Croissants.

- Inflation Kategorisierung: Bewertet die Inflation im Vergleich zum Vorjahr als negativ, neutral oder positiv. Eine positive Kategorisierung deutet auf eine steigende Inflation hin.

## Tages-bezogene Features
- Feiertag: Kennzeichnet offizielle Feiertage.

- Ferien: Markiert Ferienzeiten in S.H., in denen ggfs. mehr Ausgaben für Freizeit und Reisen zu erwarten sind. Unsere Data exploration zeigte, dass der Umsatz in den Sommermonaten höher war, als in anderen Monaten.

- Special Events: Variablen, die besondere Veranstaltungen (z. B. Kieler Triathlon, KielLauf, Fußball) kennzeichnen, die das Konsumverhalten beeinflussen können.

- Wochenende: Kennzeichnet Wochenendtage (Samstag und Sonntag), die typischerweise mit höherem Konsum von Freizeitaktivitäten verbunden sind. Zudem zeigte unsere Data exploration, dass der Umsatz am Samstag und Sonntag höher war, als an anderen Wochentagen.

## Wetter-bezogene Features
- Jahreszeit: Frühling (März, April, Mai) - Sommer (Juni, Juli, August) - Herbst (September, Oktober, November) - Winter (Dezember, Januar, Februar); unesre Data exploration zeigte, dass der Umsatz in den Sommermonaten höher war, als in den anderen Monaten. Hier gibt es eine Korrelation mit "Ferien"

- Gefühlte Temperatur: Jahreszeit-abhängige Einordnung der jeweiligen Tagestemperatur (Frühling: kalt <= 10, mild <= 20, darüber: warm; Sommer: kalt <= 15, mild <= 25, darüber: warm; Herbst: kalt <= 10, mild <= 20, darüber: warm; Winter: kalt <= 0, mild <= 10, darüber: warm).
