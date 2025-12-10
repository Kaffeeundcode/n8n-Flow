n8n-Flow

Automatisierung mit n8n – praktische Workflows für den IT-Alltag.

Dieses Repository enthält n8n-Workflows mit Fokus auf Microsoft Intune, Automatisierung von Routineaufgaben und Integration von Cloud-Services.

⸻

🚀 Überblick

Ziele dieses Projekts:
	•	Wiederverwendbare n8n-Flows für typische Admin- und Automatisierungsaufgaben
	•	Fokus auf Intune, Microsoft 365 und angrenzende Dienste
	•	Klar strukturierte Workflows, die leicht angepasst und erweitert werden können

Die Flows sind so aufgebaut, dass sie:
	•	möglichst verständlich benannt sind
	•	Kommentare und Hinweise im Workflow enthalten
	•	als Grundlage für eigene Automatisierungen dienen

⸻

📁 Repository-Struktur

n8n-Flow/
├─ Intune_Workflows/   – n8n-Flows rund um Microsoft Intune
└─ README.md           – diese Übersicht

Weitere Ordner/Kategorien können im Laufe der Zeit hinzukommen (z. B. Monitoring, Reporting, Drittanbieter-APIs).

⸻

⚙️ Voraussetzungen

Um die Flows zu verwenden, benötigst du in der Regel:
	•	Eine funktionierende n8n-Instanz
	•	selbst gehostet (Docker, VM, etc.) oder
	•	n8n Cloud
	•	Die passenden Credentials (z. B. Azure AD / Microsoft Graph, Webhook-URLs, API-Keys)
	•	Zugriff auf deinen Intune-/Microsoft-365-Tenant mit den notwendigen Berechtigungen

Details zu benötigten Credentials und Berechtigungen findest du – soweit nötig – in den Beschreibungen der jeweiligen Workflows.

⸻

🧪 Schnellstart
	1.	Dieses Repository klonen oder die gewünschten Workflows aus dem Ordner Intune_Workflows herunterladen.
	2.	In n8n einloggen und den jeweiligen Flow importieren:
	•	In der n8n UI auf „Flows“ / „Workflows“ gehen
	•	„Import“ wählen und die JSON-Datei hochladen
	3.	Benötigte Credentials in n8n anlegen (z. B. Microsoft Graph, Webhooks, SMTP etc.).
	4.	Die Platzhalter in den Nodes (z. B. Tenant-ID, URLs, E-Mail-Adressen) an deine Umgebung anpassen.
	5.	Workflow testen und danach aktivieren (Trigger einschalten, Zeitplan definieren, etc.).

Bitte teste neue Flows immer zuerst in einer Test- oder Nicht-Produktivumgebung.

⸻

🧩 Kategorie: Intune_Workflows

Im Ordner Intune_Workflows findest du Flows, die z. B.:
	•	Intune-Informationen zyklisch abfragen und aufbereiten
	•	Reports erzeugen (z. B. Geräte- oder Compliance-Übersichten)
	•	Ereignisse per E-Mail, Teams oder anderen Kanälen melden
	•	mit PowerShell-Skripten oder Graph-API-Endpunkten zusammenarbeiten

Die genaue Funktion jedes Flows ist in der Beschreibung des Workflows in n8n sowie ggf. in Kommentaren innerhalb des Flows dokumentiert.

⸻

🤝 Beiträge / Contributing

Beiträge sind willkommen!

So kannst du mitmachen:
	1.	Repository forken
	2.	Eigene n8n-Flows ergänzen oder bestehende verbessern
	3.	Änderungen kurz dokumentieren (Beschreibung, benötigte Credentials, Use-Case)
	4.	Pull Request erstellen

Fehler, Ideen oder Erweiterungsvorschläge kannst du gerne als GitHub Issue einreichen.

⸻

📜 Lizenz

Dieses Projekt steht unter der MIT-Lizenz (sofern nicht anders angegeben).
Du kannst die Flows im Rahmen der Lizenz frei verwenden, anpassen und weitergeben.

⸻

👤 Autor

Mattia Cirillo
Ersteller von kaffeeundcode – Automatisierung, Intune & n8n in der Praxis.

Wenn dir diese Flows helfen, freue ich mich über einen ⭐ auf GitHub.
