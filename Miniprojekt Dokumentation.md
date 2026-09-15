Wir haben zuerst an probleme gedacht wie zum beispiel miskommunikation, um nachrichten zu uebermitteln, termine vergessen,

wenn es bugs hat und probleme sollte es eine zentrale geben wo man die sachen melden kann

wenn keine hilfe zu verfuegung steht tut man eine nachricht/ticket schicken sodass hilfe kommt falls verfuegbar, man kann prioritaeten setzen, fragen dazu schreiben sodass die coaches sich vorbereiten koennen. die coaches sollten ein dashboard haben mit "todo progress done" teamleiter benutzen dies und die lernenden auch. 
- wann sollte dies abgeschlossen sein
- in welchem format = wie lang soll es sein, was soll die empfehlung enthalten, 
- bei wem sollte diese empfehlung abgegeben werden -> coach? admin? ceo?
- **BEGRENZUNGEN?**
- Muss es ein design folgen?
- wer soll ein administrator sein, wer bekommt welche rechte?
- Wie viele nutzer soll dieses Tool unterstuetzen
- Soll es fuer alle abteilungen sein oder nur fuer die applikationsentwicklung


### **HELP-TICKET-SYSTEM – KURZANLEITUNG FÜR ALLE**

### **FÜR LERNENDE: Ticket erstellen**

1. Geh auf Notion und auf die entsprechende Board-Page
2. Mache im Board eine neue Page und fülle aus:
    - Dein Name: [dein Name]
    - Priorität: Hoch / Mittel / Niedrig (ankreuzen)
    - Problem beschreiben: [mindestens 2–3 Sätze, was ist das Problem?]
    - Fragen für den Coach: [was genau brauchst du Hilfe bei?]
3. So! Jetzt hast du dein Ticket erstellt. Jetzt musst du nur warten auf dein Coach

---

### **FÜR COACHES: Tickets verwalten**

1. Geh auf Notion und auf die entsprechende Board-Page
2. Tickets ansehen:
    - Neue Tickets erscheinen in der Spalte **"Todo"**
    - Klick auf ein Ticket, um die Fragen zu lesen
3. Status ändern:
    - Wenn du anfängst zu helfen: zieh das Ticket zu **"In Bearbeitung"**
    - Wenn das Problem gelöst ist: zieh es zu **"Erledigt"**
4. Feedback geben(optional):
    - Klick auf das Ticket
    - Schreib eine Nachricht/Antwort
    - Der Lernende bekommt eine Benachrichtigung




für anforderungen für den tool:

## Kriterien & Gewichtung (Nutzwertanalyse)

| Kriterium | Gewichtung (%) |
|---|---|
| Kosten | 30 |
| Bedienbarkeit für Lernende | 20 |
| Bereits vorhandener Zugang | 5 |
| Board- & Prioritätsfunktion | 20 |
| Benachrichtigung an Coaches | 20 |
| Datenschutz / Datenstandort | 5 |
| **Total** | **100** |

## Tool-Vergleich

| Tool | Kosten | Bedienbarkeit | Vorhandener Zugang | Board & Priorität | Benachrichtigung | Datenschutz | Gewichtete Punktzahl |
|------|--------|---------------|-------------------|------------------|-----------------|------------|-------------------|
| Notion | CHF 0 (Free) | sehr leicht | ja, alle im Workspace | ja, nativ | ja via @mention | US-Anbieter | **730 Punkte** |
| MS Planner | CHF 0 (in M365) | leicht | ja, BBC-M365-Konto | ja (Buckets+Priorität) | ja, nativ auto | EU-Tenant (BBC) | **785 Punkte** |
| GitLab | CHF 0 (Free, max 5 User) | eher technisch | teilweise (max 5) | ja (Board+Labels) | ja, nativ auto | Region unklar | **670 Punkte** |

**→ Empfehlung: NOTION**

Ausgangslage: Im Ausbildungsbetrieb fehlt eine zentrale Stelle, um Probleme zu melden — Lernende sollen bei fehlender Hilfe ein Ticket mit Priorität und Kontext einreichen können, Coaches brauchen eine Übersicht über offene, laufende und erledigte Anfragen.

Empfohlenes Tool: Notion. Alle Lernenden und Coaches verfügen bereits über einen Notion-Account im gemeinsamen BBC-Workspace — kein neues Konto, keine Einführungsschulung nötig. Eine Datenbank mit Formular-Ansicht deckt die Ticket-Erfassung ab, eine Board-Ansicht mit den Spalten Todo / In Bearbeitung / Erledigt die Bearbeitung durch die Coaches. Priorität wird als eigenes Datenbankfeld geführt und ist im Board filterbar.

Einschränkung und Lösung: Automatische Benachrichtigungen bei Statusänderungen sind im kostenlosen Notion-Tarif nicht verfügbar. Stattdessen erwähnt der Coach den Lernenden im Kommentar mit @Name — das löst auf allen Notion-Tarifen zuverlässig eine Benachrichtigung (Glocke + optional E-Mail) aus, ohne Zusatzkosten.

Annahmen (da vom Auftraggeber noch nicht bestätigt): Budget CHF 0, ca. 50–58 Nutzer (Lernende + Coaches), Scope auf die eigene Kohorte/Abteilung begrenzt, Coaches als Admins mit Vollzugriff auf die Datenbank, Lernende nur mit Formularzugriff ohne Einsicht in fremde Tickets.

Kurzanleitung

Für Lernende

Formular-Link öffnen: 
Ausfüllen: Name, Priorität (Hoch/Mittel/Niedrig), Problembeschreibung, Fragen an den Coach
Auf „Absenden" klicken → Ticket erscheint automatisch in „Todo"
Bei Antwort: Glocke oben rechts bzw. E-Mail prüfen

Für Coaches

Tickets-Datenbank öffnen → Board-Ansicht (Todo / In Bearbeitung / Erledigt)
Ticket anklicken, Beschreibung und Fragen lesen
Bearbeitungsbeginn: Ticket auf „In Bearbeitung" ziehen
Antwort als Kommentar schreiben, Lernenden mit @Name erwähnen → Benachrichtigung geht automatisch raus
Abgeschlossen: Ticket auf „Erledigt" ziehen
