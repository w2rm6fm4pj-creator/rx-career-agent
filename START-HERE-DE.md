# Hier starten: Dein persönlicher Karriereassistent

**Deutsch** · [English](START-HERE.md)

Du musst weder programmieren können noch GitHub verstehen. Mit diesem Paket bekommt dein KI-Assistent eine Anleitung, mit der er dich Schritt für Schritt bei der Jobsuche und bei Bewerbungen unterstützt. Du bringst deine Erfahrung ein und triffst die wichtigen Entscheidungen.

Ein „Skill“ ist eine wiederverwendbare Anleitung für einen KI-Assistenten. Dieses Paket heißt **rx-career-agent**. Diesen Namen und die Dateinamen bitte unverändert lassen. Alles andere kannst du mit dem Assistenten auf Deutsch besprechen.

Die erste Sitzung ist erfolgreich, wenn der Assistent deine Ziele versteht, dein eigenes RX-Konto geprüft hat und du einen ersten Lebenslaufentwurf ansehen kannst. Probiere danach zunächst eine Bewerbung aus.

Die englischen Bezeichnungen von Schaltflächen stehen unten jeweils dabei, damit du sie auch in einer englischen Benutzeroberfläche findest. Je nach Sprache und App-Version können sie anders heißen. Die verlinkten Herstelleranleitungen sind teilweise auf Englisch; die nötigen Schritte stehen hier auf Deutsch.

## 1. Das Paket herunterladen

Öffne die GitHub-Seite, über die du diese Anleitung erhalten hast. Klicke auf **rx-career-agent.zip** und anschließend auf die Schaltfläche zum Herunterladen. Lass die Datei zunächst im Ordner **Downloads**. Du brauchst diese einzelne ZIP-Datei, nicht das gesamte GitHub-Projekt.

Falls die Seite nicht aufgeht, bitte die Person, die sie mit dir geteilt hat, um Zugriff. Sie kann dir auch die ZIP-Datei und diese Anleitung direkt schicken. Dafür brauchst du kein GitHub-Konto.

## 2. Deinen KI-Assistenten auswählen

### Möglichkeit A: Codex auf deinem Computer

Mit dieser Umgebung wurde der Ablauf ursprünglich entwickelt. Öffne deine Desktop-App und wähle Codex. Die aktuelle OpenAI-Anleitung beschreibt die Auswahl über das ChatGPT-Menü. Wähle **Local**, also die Arbeit auf deinem Computer. [Offizielle Anleitung](https://learn.chatgpt.com/docs/environments/modes)

Lege auf deinem Computer einen privaten Ordner namens **Meine Karriere** an. Öffne ihn in der App als lokales Projekt über die Funktion zum Öffnen eines Projekts oder Ordners. Hier werden später dein Profil, Entwürfe und Bewerbungsübersichten gespeichert. Verwende dafür einen eigenen Ordner, getrennt vom heruntergeladenen GitHub-Projekt. Ein gewöhnliches ChatGPT-Projekt im Browser hat nicht automatisch Zugriff auf Ordner auf deinem Computer. [Informationen zu Projekten](https://learn.chatgpt.com/docs/projects)

Kopiere diese Nachricht in eine neue Unterhaltung in diesem lokalen Projekt:

> Hilf mir, RX Career Agent einzurichten. Ich habe keine technischen Vorkenntnisse. Bitte begleite mich auf Deutsch. Die Datei rx-career-agent.zip liegt in meinem Downloads-Ordner. Prüfe das Paket, installiere den enthaltenen Ordner rx-career-agent als Projekt-Skill unter .agents/skills und kontrolliere, ob die zugehörigen Anleitungen vorhanden sind. Bewahre meine persönlichen Karriereunterlagen privat in diesem Projekt auf. Sage mir, ob ich danach eine neue Aufgabe starten muss, damit der Skill erkannt wird. Prüfe anschließend, welche Werkzeuge für Recherche, Lebensläufe, PDFs und Browserbedienung verfügbar sind. Erkläre fehlende Einrichtungsschritte einzeln und verständlich.

Die technischen Ordner lässt du den Assistenten anlegen. Starte nach der Installation bei Bedarf eine neue Aufgabe im selben Projekt. Schreibe dann:

> Nutze $rx-career-agent und hilf mir auf Deutsch beim Einstieg.

Die App muss den Skill erkennen, damit sie seine Anleitung verwenden kann. [Offizielle Informationen zu Skills](https://learn.chatgpt.com/docs/build-skills)

Falls deine App andere Menüs oder keine Codex-Auswahl zeigt, nutze die Herstelleranleitung oder die Claude-Variante unten. Welche Funktionen verfügbar sind, kann von deinem Konto und den Einstellungen deiner Organisation abhängen.

### Möglichkeit B: Claude

Aktiviere bei Bedarf unter **Settings → Capabilities** die Funktion **Code execution and file creation**, also das Ausführen von Code und Erstellen von Dateien. Öffne anschließend **Customize → Skills → + → Create skill → Upload a skill**. Lade **rx-career-agent.zip** hoch und aktiviere den Skill. Bei einem Firmenkonto können diese Funktionen eingeschränkt sein. [Offizielle Claude-Anleitung](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

Beginne eine Unterhaltung mit dieser Nachricht:

> Nutze den Skill rx-career-agent. Bitte begleite mich auf Deutsch und ohne technische Vorkenntnisse vorauszusetzen. Hilf mir Schritt für Schritt, mein eigenes RX-Resume-Konto einzurichten und meine Jobsuche vorzubereiten. Prüfe zuerst, ob du Stellen recherchieren, eine Verbindung zu RX herstellen, PDFs erstellen und prüfen sowie Bewerbungsseiten bedienen kannst. Sage mir, welche Schritte du selbst erledigen kannst und welche ich übernehmen muss. Bitte mich nicht, einen API-Schlüssel in diese Unterhaltung hochzuladen.

Das Skill-Format ist mit Claude kompatibel. Der vollständige Ablauf dieses Pakets wurde in Claude noch nicht getestet. Die Installation allein verbindet keine Konten und schaltet keine Browsersteuerung frei. Fehlt eine Funktion, soll der Assistent trotzdem die Inhalte vorbereiten und dich durch den manuellen Schritt führen.

### Geht das auch im normalen ChatGPT-Chat oder in Work?

Du kannst dort deinen Lebenslauf besprechen und Chancen bewerten. Für den gesamten Ablauf muss deine Umgebung aber tatsächlich den Skill und die benötigten Werkzeuge bereitstellen. Die ZIP-Datei ist ein eigenständiger Skill, kein veröffentlichtes ChatGPT-Plugin. Sie in einen gewöhnlichen Chat hochzuladen bedeutet noch nicht, dass sie installiert ist oder Bewerbungen automatisch ausgefüllt werden können.

## 3. Dein eigenes RX-Resume-Konto erstellen

RX Resume heißt auch **Reactive Resume**. Öffne [rxresu.me](https://rxresu.me) und folge den Schritten zur Registrierung oder Anmeldung. Verwende deine eigene E-Mail-Adresse oder eine angebotene Anmeldemethode. Bestätige deine Anmeldung selbst und speichere deine Zugangsdaten in deinem Passwortmanager.

Du kannst den Assistenten so um Hilfe bitten:

> Hilf mir beim Einrichten von Reactive Resume. Öffne nach Möglichkeit die offizielle Website und führe mich durch die einzelnen Schritte. Mein Passwort und eventuelle Bestätigungscodes gebe ich selbst ein. Prüfe nach der Anmeldung, dass es wirklich mein Konto ist, bevor du etwas veränderst.

Wenn du bereits ein Konto hast, melde dich dort an. Ist noch ein Familienmitglied angemeldet, wechsle zuerst das Konto. Der Assistent muss prüfen, wem das Konto gehört; ein vertrauter Lebenslauftitel reicht dafür nicht aus. Ein leeres Konto ist in Ordnung: Aus deinem bisherigen Lebenslauf kann später ein erster Entwurf entstehen.

## 4. RX mit deinem Assistenten verbinden

### Am einfachsten: Verbindung durch Anmeldung

Frage den Assistenten, ob deine App die offizielle RX-Verbindung mit Anmeldung unterstützt. RX beschreibt dafür die Adresse **https://rxresu.me/mcp**, unter anderem für eine benutzerdefinierte Verbindung in Claude. Wenn deine App diese Möglichkeit bietet, füge die Verbindung in ihren Einstellungen hinzu und melde dich bei RX an. Lass dich vom Assistenten durch die aktuellen Bildschirme führen. So brauchst du möglicherweise keinen API-Schlüssel zu kopieren. [RX-Anleitung zur Verbindung](https://docs.rxresu.me/guides/using-the-mcp-server)

### Alternative: API-Schlüssel in einer privaten Datei

Ein API-Schlüssel funktioniert ähnlich wie ein Passwort. Damit kann der Assistent auf dein RX-Konto zugreifen. Gemeint ist ein **Schlüssel von RX**, nicht von OpenAI oder Anthropic.

1. Öffne in RX **Settings → API Keys**, also die Einstellungen für API-Schlüssel.
2. Wähle **Create a new API key**. Gib ihm einen Namen, zum Beispiel **Mein Karriereassistent**, wähle ein Ablaufdatum und erstelle ihn.
3. Kopiere den angezeigten Schlüssel. RX zeigt ihn nur einmal an. [RX-Anleitung zu API-Schlüsseln](https://docs.rxresu.me/guides/using-the-api)
4. Bietet dein Assistent ein dafür vorgesehenes sicheres Eingabefeld, verwende dieses. Andernfalls kannst du bei einem Assistenten mit lokalem Dateizugriff den Schlüssel allein in einer privaten Textdatei namens **RX-Resume-Key.txt** speichern. Auf dem Mac verwendest du TextEdit und wählst vor dem Speichern **Format → In reinen Text umwandeln**; auf Englisch heißt das **Make Plain Text**. Unter Windows kannst du den Editor, auch **Notepad** genannt, nutzen. Speichere die Datei möglichst in einem privaten lokalen Ordner. Der Schreibtisch geht ebenfalls, sofern er nicht geteilt wird; er kann allerdings mit deinem Cloud-Konto synchronisiert werden.
5. Nenne dem Assistenten nur den Speicherort, nicht den Schlüssel selbst. Passe diese Nachricht an deinen tatsächlichen Speicherort an:

> Mein RX-API-Schlüssel liegt in der Datei RX-Resume-Key.txt auf meinem Schreibtisch. Verwende ihn vertraulich, um dich mit meinem Reactive-Resume-Konto zu verbinden. Zeige den Schlüssel nicht an und schreibe ihn weder in Protokolle noch in erstellte Dokumente oder GitHub. Prüfe vor Änderungen, zu welchem Konto der Schlüssel gehört.

Ein Chat im Browser kann deinen Schreibtisch nicht allein dadurch lesen, dass du einen Dateinamen nennst. Wenn der Zugriff fehlt, verwende eine unterstützte sichere Verbindung oder einen lokalen Assistenten. **Lade die Schlüsseldatei nicht als Chat-Anhang hoch und füge sie nicht dem geteilten Skill hinzu.** Eine lokale Datei legt nur fest, wo der Schlüssel gespeichert ist. Sie garantiert nicht, dass der KI-Dienst ihn niemals verarbeitet. Der Assistent soll ihn daher nicht in Ausgaben anzeigen, die an das Sprachmodell gehen.

Wenn du den Schlüssel verlierst, erstelle einen neuen. Falls er versehentlich veröffentlicht wurde, widerrufe ihn in RX und ersetze ihn. Die Person, die dir diese Anleitung gegeben hat, braucht deinen Schlüssel nicht.

**So erkennst du, dass die Verbindung steht:** Der Assistent bestätigt einen erfolgreichen Lesezugriff und prüft, wessen Konto er erreicht hat. Anschließend kontrolliert er einen neuen Entwurf oder eine Kopie, ohne deinen ursprünglichen Lebenslauf zu ändern. Eine gespeicherte Schlüsseldatei allein ist noch keine funktionierende Verbindung.

## 5. Dein Profil und deinen Lebenslauf erarbeiten

Stelle deinen aktuellen Lebenslauf bereit, bei Bedarf auch dein Portfolio oder LinkedIn-Profil. Schreibe:

> Analysiere zuerst meinen Lebenslauf und stelle mir anschließend in kleinen Runden Fragen. Hilf mir herauszuarbeiten, was ich tatsächlich geleistet habe, welche Ergebnisse ich belegen kann und welche Aufgaben ich künftig übernehmen möchte. Frage nach Arbeitsort, Reisebereitschaft, mobilem Arbeiten, Umzug, Verantwortung und Gehalt. Erhalte mein bevorzugtes Design und lasse meinen ursprünglichen Lebenslauf unverändert. Frage mich, in welcher Sprache die Bewerbungsunterlagen entstehen sollen.

Korrigiere den Assistenten, wenn er etwas übertreibt. Du solltest eine Zusammenfassung deines beruflichen Profils, klare Suchkriterien und einen Entwurf in deinem eigenen RX-Konto erhalten. Sieh dir die tatsächlich exportierte PDF-Datei an. Der Assistent soll lesbaren Text, Gestaltung und Dateigröße prüfen. Ein ATS-Test prüft Aspekte der maschinellen Lesbarkeit für Bewerbersysteme; sein Ergebnis garantiert keine erfolgreiche Bewerbung.

## 6. Eine erste Bewerbung vorbereiten

> Suche eine kurze Liste passender, nachweislich noch offener Stellen. Bewerte getrennt, wie attraktiv die Stelle für meine Ziele ist und wie gut mein Profil zu den Anforderungen passt. Erkläre wesentliche Lücken und offene Fragen. Prüfe meine bisherigen Bewerbungen, damit wir uns nicht doppelt bewerben.

Wähle eine Stelle aus. Schreibe anschließend:

> Bereite diese Bewerbung vor. Passe eine Kopie meines Lebenslaufs und ein Anschreiben an die Stelle an. Prüfe die fertigen PDFs sowohl visuell als auch auf lesbaren Text. Recherchiere das Gehalt und frage mich nach meiner Gehaltsentscheidung. Fülle das Formular aus und hänge die Unterlagen an, soweit deine Werkzeuge das ermöglichen. Halte direkt vor dem Absenden an und zeige mir die fertig vorbereitete Bewerbung.

Konten bei Arbeitgebern, Anmeldebestätigungen und Fragen, die der Assistent nicht verlässlich beantworten kann, übernimmst du selbst. Ein freigegebener Gehaltswunsch gilt nur für den jeweiligen Arbeitgeber. Wenn alles passt, gib ausdrücklich das Absenden dieser fertigen Bewerbung frei. Der Assistent soll erst nach einer bestätigten Übermittlung „abgesendet“ vermerken. Ein gespeicherter Entwurf ist keine Eingangsbestätigung.

## 7. Später weiterarbeiten

Kehre in dasselbe private Projekt zurück oder stelle die gespeicherten Karriereunterlagen wieder bereit. Diese Nachrichten helfen dir:

- „Setze beim gespeicherten Arbeitsstand fort und zeige mir, was als Nächstes ansteht.“
- „Suche neue Stellen und berücksichtige auch diese E-Mails mit Jobempfehlungen.“
- „Bereite Bewerbungen für die ersten beiden Stellen vor und recherchiere zuerst das Gehalt.“
- „Erfasse diese Rückmeldung und hilf mir bei der Vorbereitung auf das Vorstellungsgespräch.“
- „Speichere unsere heutigen Entscheidungen und den nächsten Schritt, bevor wir aufhören.“

Zugriff auf E-Mails und regelmäßige automatische Suchen müssen separat eingerichtet und von dir freigegeben werden. Die Installation allein lässt den Assistenten nicht dauerhaft im Hintergrund arbeiten.

## Wenn etwas nicht klappt

| Problem | Nächster Schritt |
| --- | --- |
| Der Skill wird nicht gefunden. | Installation und Aktivierung prüfen, dann eine neue Aufgabe starten. Den Assistenten die installierten Dateien kontrollieren lassen. |
| RX zeigt das Konto einer anderen Person. | Änderungen stoppen und ins eigene Konto wechseln. Auch den Zugang über den API-Schlüssel separat prüfen. |
| Die Schlüsseldatei kann nicht gelesen werden. | Eine unterstützte Verbindung nutzen oder dem lokalen Assistenten Zugriff auf die konkrete Datei geben. Den Schlüssel nicht in den Chat kopieren. |
| RX meldet „Unauthorized“, also fehlende Berechtigung. | Ablaufdatum, Konto und Verbindung prüfen. Einen abgelaufenen Schlüssel ersetzen oder die Verbindung neu herstellen. |
| Der Assistent kann die Bewerbungsseite nicht bedienen. | Die vorbereiteten Unterlagen verwenden und sich durch die manuellen Schritte führen lassen. |
| Beim Absenden erscheint eine Zeitüberschreitung. | Erst im Portal oder nach einer Bestätigung sehen, bevor erneut abgesendet wird. So vermeidest du doppelte Bewerbungen. |

Dies ist eine erste Erprobungsversion. Werkzeuge, Abonnements und Einstellungen unterscheiden sich. Der erste vollständige Durchlauf zeigt auch, was in deiner Umgebung tatsächlich funktioniert.
