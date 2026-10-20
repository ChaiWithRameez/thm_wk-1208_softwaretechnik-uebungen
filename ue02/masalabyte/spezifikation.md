<!-- GitHub-Benutzername: ChaiWithRameez -->

# Entwurf der Spezifikation für den THM-Terminplaner

## 1. Einleitung und Zielsetzung
Dieses Dokument spezifiziert die Anforderungen an die neue Software zur Terminplanung an der THM.
* **Beispiel:** "Das System ersetzt die bisherige Terminvereinbarung per Zettel und E-Mail durch eine zentrale Webanwendung mit Hochschul-Login."

## 2. Benutzerrollen und Rechte
Übersicht über die im System agierenden Akteure.
* **Beispiel:** 
  * *Studierende:* Können freie Termine einsehen und buchen.
  * *Lehrende:* Können Zeitfenster für Sprechstunden definieren.

## 3. Funktionale Anforderungen
Detaillierte Beschreibung der Systemfunktionen.
* **Beispiel:** "Nach erfolgreicher Buchung eines Sprechstundentermins generiert das System automatisch eine `.ics`-Datei und sendet eine Bestätigung."

## 4. Schnittstellen (Spezifikation der API)
Vorgaben für die Anbindung externer Systeme und KI-Agenten.
* **Beispiel:** `GET /api/v1/slots?department=mnd` liefert eine Liste aller verfügbaren Zeitfenster im JSON-Format.

## 5. Nicht-funktionale Anforderungen
Qualitätsmerkmale wie Sicherheit, Leistung und Verfügbarkeit.
* **Beispiel:** "Die Authentifizierung aller Benutzer muss zwingend über den zentralen SSO-Dienst der THM erfolgen."