# WebSuite

**Der souveräne Workspace für den Mittelstand** — Dateien, Mail, Office, Chat und Video in
einer Oberfläche, aus einem Rechenzentrum in Deutschland, mit Root-Zugang.
Mehr unter [websuite.io](https://websuite.io).

Der Code ist offen und heisst **Modulstack Workspace**: ein Kern und Module, die sich
installieren, abschalten und einzeln aktualisieren lassen. Darunter läuft
[Libre Workspace](https://codeberg.org/Libre_Workspace/libre-workspace), unverändert.

> **Entwickelt wird auf Forgejo:** [forgejo.bit-tag.com/websuite-io](https://forgejo.bit-tag.com/websuite-io)
> — dort liegen Code, Issues und Beiträge. GitHub ist nur das Schaufenster.
>
> **Status:** Veröffentlichung in Vorbereitung. Die Repositories werden öffentlich, sobald
> Lizenz- und Markenfragen geklärt sind.

## Kern, Module, Apps

| Repository | Was | Version | Code |
|---|---|---|---|
| `modulstack` | **Kern** — Anmeldung, Rahmen, Module installieren und aktualisieren, Widgets | 1.0.1 | bald öffentlich |
| `modulstack-dashboard-modul` | **Dashboard** — die Startseite mit Widgets: Apps, Kennzahlen, Server | 0.1.0 | bald öffentlich |
| `modulstack-scripts-modul` | **Skript** — Gesprächsskripte üben, mit Wiederholung nach Plan | 0.8.1 | bald öffentlich |
| `modulstack-crm-modul` | **CRM** — Organisationen, Kontakte, Leads, Anrufe mit dem Skript daneben | 0.1.1 | bald öffentlich |
| `modulstack-workspace-app` | **Modulstack Workspace** — die Zusammenstellung aus Kern und Modulen | — | bald öffentlich |

**In Arbeit:** Desktop (Fenster und Taskleiste), Store (Module und Server-Apps installieren),
Libre Workspace (Apps, Benutzer und Backups des Servers).

## Lizenz und Marke

Modulstack und seine Module stehen unter der **GNU Affero General Public License, Version 3
oder später** (`AGPL-3.0-or-later`), Copyright Dustin Ludwig. **WebSuite** ist eine Marke und
nicht Teil dieser Lizenz: Wer den Code unter eigenem Namen betreibt, darf das jederzeit;
der Name WebSuite steht nur auf offiziellen Builds und bei lizenzierten Partnern.
