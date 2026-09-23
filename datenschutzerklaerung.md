# 🛡️ Datenschutzerklärung für „Quartett Master – Supertrumpf“

**Geltungsbereich:** Mobile App „Quartett Master – Supertrumpf“ (`de.quartett.app.quartett_app`)  
**Stand:** September 2026  

---

## 1. Verantwortlicher für die Datenverarbeitung

Verantwortlicher im Sinne der Datenschutz-Grundverordnung (DSGVO) und anderer nationaler Datenschutzgesetze ist:

**Sven Schäfer**  
E-Mail: [kontakt@sl.mohadipe.de](mailto:kontakt@sl.mohadipe.de) *(oder github@mohadipe.de)*  
Website: [https://github.com/Mohadipe-Group/quartett-project-repo](https://github.com/Mohadipe-Group/quartett-project-repo)  

---

## 2. Grundsätze der Datenverarbeitung (Privacy by Design & Datensparsamkeit)

Der Schutz Ihrer Daten und Ihrer Privatsphäre ist für uns von höchster Bedeutung. Unsere App ist nach dem Grundsatz der **Datensparsamkeit** und **Privacy by Design** konzipiert:

* **Anonymer Gast-Modus:** Sie können das Spiel vollständig nutzen, ohne Ihren Klarnamen, eine E-Mail-Adresse oder eine Telefonnummer anzugeben.
* **Keine Werbetracker:** Die App bindet **keine** invasiven Werbenetzwerke oder Tracking-SDKs (wie z. B. Google AdMob, Unity Ads oder Facebook/Meta SDK) ein.
* **Kein Freitext-Chat:** Im Online-Multiplayer gibt es keinen freien Text-Chat, sondern ausschließlich vorgefertigte Emojis und Schnellreaktionen. Dies schützt insbesondere jüngere Spieler vor der Weitergabe persönlicher Daten.
* **Serverstandort in der EU:** Unser Backend läuft in einem Rechenzentrum in Frankfurt am Main (Deutschland).

---

## 3. Welche Daten werden erhoben und zu welchem Zweck verarbeitet?

### 3.1 Bereitstellung der App & Spielfunktionen (Art. 6 Abs. 1 lit. b DSGVO)
Zur Bereitstellung des Spiels und zur Ermöglichung von Online-Duellen verarbeiten wir:
* **Zufällige Benutzer-ID (UUID):** Beim ersten App-Start wird ein anonymes Spielerprofil erstellt.
* **Spielername (Pseudonym):** Ein von Ihnen frei wählbarer Spitzname (Default z. B. „Spieler #1234“).
* **Avatar-Symbol:** Ein aus den Spielgrafiken ausgewähltes Profilbild.
* **Spieldaten:** Level, Erfahrungspunkte (XP), erspielte Münzen (Coins), Elo-Rating, Spielstatistiken (gewonnene/verlorene Duelle) sowie freigeschaltete Kartendecks.
* **Duell- und Match-Daten:** Aktuelle Spielzüge, Match-Code für private Räume und Runden-Ergebnisse.

### 3.2 Technische Berechtigungen der App
Die App fordert ausschließlich Berechtigungen an, die für die Kernfunktion zwingend erforderlich sind:
* **Internetzugriff (`android.permission.INTERNET`, `ACCESS_NETWORK_STATE`):** Erforderlich für den Abgleich von Spieldaten, Online-Multiplayer und Fehlerberichte.
* **Keine sensiblen Berechtigungen:** Die App fordert **weder** Standortdaten (GPS), Kamera-, Mikrofon-, noch Kontakte- oder Speicherzugriff auf private Fotos an.

### 3.3 Fehlerüberwachung & Stabilitätsdiagnose via Sentry (Art. 6 Abs. 1 lit. f DSGVO)
Zur Gewährleistung der IT-Sicherheit und Fehlerbehebung setzen wir **Sentry** ein (Anbieter: Functional Software, Inc., 45 Fremont Street, 8th Floor, San Francisco, CA 94105, USA).

* **Erfasste Daten:** Im Falle eines App-Absturzes oder Fehlers werden technische Diagnosedaten übertragen: Gerätemodell, Betriebssystem-Version, App-Version, Zeitpunkt und technischer Stacktrace (Programmcode-Ablauf beim Absturz).
* **Anonymisierung:** IP-Adressen werden vor der Speicherung gekürzt. Personenbezogene Daten werden aus Fehlermeldungen herausgefiltert.
* **Opt-Out (Widerspruchsrecht):** Sie können die Übermittlung von Fehlerberichten jederzeit in den App-Einstellungen unter **„Einstellungen ➔ Fehlerberichte senden“** per Schalter deaktivieren.

### 3.4 In-App-Käufe via Google Play Billing (Art. 6 Abs. 1 lit. b DSGVO)
Sofern Sie optionale Spielinhalte (z. B. Kartendecks oder Kosmetika) erwerben:
* Die Zahlungsabwicklung erfolgt ausschließlich über den **Google Play Store** (Google Ireland Limited, Gordon House, Barrow Street, Dublin 4, Irland).
* Wir erhalten und speichern **zu keinem Zeitpunkt** Ihre Zahlungs- oder Kreditkartendaten. Google übermittelt uns lediglich ein kryptografisches Token zur Bestätigung des Kaufs, um die Inhalte in Ihrem Profil freizuschalten.

---

## 4. Eingesetzte Dienstleister & Datenübermittlung

Wir setzen zur Bereitstellung der Dienste folgende Auftragsverarbeiter ein, mit denen entsprechende Datenschutzverträge (Art. 28 DSGVO) bestehen:

1. **Supabase Inc. (Backend & Datenbank):**
   * Zweck: Benutzerverwaltung, Speicherung der Spielstände und Realtime-Multiplayer.
   * Server-Standort: **Frankfurt am Main, Deutschland** (AWS Region `eu-central-1`).
   * Verschlüsselung: Sämtliche Datenübertragungen erfolgen verschlüsselt über TLS 1.3 / HTTPS / WSS.
2. **Sentry (Functional Software, Inc.):**
   * Zweck: Crash-Reporting und Fehleranalyse.
   * Garantien: EU-Standardvertragsklauseln (SCC) und Data Privacy Framework (DPF).
3. **Google Play Store (Google Ireland Limited):**
   * Zweck: Verteilung der App-Installationsdateien, Updates und Zahlungsabwicklung.

---

## 5. Speicherdauer & Kontolöschung (Art. 17 DSGVO)

* **Speicherdauer:** Ihre Profildaten und Statistiken bleiben gespeichert, solange Ihr Spielerkonto aktiv ist.
* **Vollständige Kontolöschung:** Sie können Ihr Spielerkonto und sämtliche damit verknüpften Daten (Inventar, Matches, Freundschaften, Statistiken) **jederzeit direkt in der App** unter **„Einstellungen ➔ Konto und Spieldaten unwiderruflich löschen“** sofort und rückstandslos entfernen (`ON DELETE CASCADE`).

---

## 6. Ihre Rechte als betroffene Person

Nach der DSGVO stehen Ihnen folgende Rechte zu:
* **Recht auf Auskunft (Art. 15 DSGVO):** Sie können Auskunft über Ihre von uns verarbeiteten personenbezogenen Daten verlangen.
* **Recht auf Datenübertragbarkeit (Art. 20 DSGVO):** In den Profileinstellungen der App können Sie mit einem Klick einen maschinenlesbaren **JSON-Datenexport** aller gespeicherten Profildaten herunterladen.
* **Recht auf Berichtigung (Art. 16 DSGVO):** Sie können die Berichtigung unrichtiger Daten verlangen.
* **Recht auf Löschung (Art. 17 DSGVO):** Sie können die unverzügliche Löschung Ihrer Daten verlangen oder diese selbst in der App durchführen.
* **Recht auf Widerspruch (Art. 21 DSGVO):** Sie können der Datenverarbeitung im Rahmen der gesetzlichen Vorgaben widersprechen (z. B. Sentry-Opt-Out in der App).
* **Beschwerderecht bei einer Aufsichtsbehörde (Art. 77 DSGVO):** Sie haben das Recht, sich bei einer Datenschutz-Aufsichtsbehörde über die Verarbeitung Ihrer Daten zu beschweren.

---

## 7. Schutz von Minderjährigen

Das Spiel richtet sich an Spieler aller Altersgruppen (USK 0 / PEGI 3). Wir erheben wissentlich keine personenbezogenen Daten von Kindern unter 16 Jahren. Sollten Sie feststellen, dass ein Kind ohne Zustimmung der Erziehungsberechtigten Daten übermittelt hat, kontaktieren Sie uns bitte zur sofortigen Löschung.

---

## 8. Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung anzupassen, wenn sich unsere App oder rechtliche Vorgaben ändern. Die aktuelle Fassung ist stets in der App sowie unter der offiziellen Store-URL einsehbar.
