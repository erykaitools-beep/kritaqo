# Kritaqo — Projektbeschreibung für Bewerbungen

[Produktüberblick](../README.md) · [Windows-Testanleitung](TESTING.md) ·
[Aktueller Umfang und Grenzen](../ROADMAP.md)

## Projektprofil

Kritaqo ist ein eigenständiges, KI-gestützt entwickeltes Desktop-Projekt für
Gespräche, nachvollziehbare Zusammenarbeit mehrerer Modelle und Projekte auf
explizit verbundenen eigenen Computern. Nutzer wählen ein führendes Modell
und können Beiträge von Planer, Reviewer und Koordinator verfolgen.

Meine Rolle umfasst die Produktidee, Anforderungen, Priorisierung und
Steuerung der KI-gestützten Umsetzung. Der Schwerpunkt liegt auf dem
nutzbaren Ablauf rund um Modelle: Konten verbinden, Gespräche wiederfinden,
Aufgaben abbrechen und die Verfügbarkeit anderer Computer erkennen.

Öffentlich verfügbar sind eine frühe Windows-Alpha, Versionshinweise und
Testanleitungen auf Englisch und Polnisch. Der Anwendungscode ist privat.
Die Versionshinweise berichten automatisierte Tests; Erstinstallationen
auf weiteren Windows-Systemen benötigen weiterhin Rückmeldungen.
Das Projekt ist daher als Produktprototyp mit veröffentlichtem Testbuild
einzuordnen.

## Kurze Fassung für den Lebenslauf

### Kritaqo — Desktop-Workspace für KI | Eigenprojekt, frühe Windows-Alpha

- Konzeption und Steuerung einer KI-gestützten Umsetzung für gespeicherte
  Gespräche, Modellauswahl und sichtbare Planer-/Reviewer-Abläufe.
- Gestaltung von Projektübersichten über explizit verbundene eigene Computer,
  einschließlich gespeicherter Offline-Zustände.
- Veröffentlichung eines Windows-Testbuilds mit Testanleitungen,
  Feedback-Kanälen und dokumentierten Grenzen bei Konten, Updates und Daten.

## Nachweise und Grenzen

Der [veröffentlichte Testbuild](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.18-alpha.2)
enthält einen Installer und eine Prüfsumme. Ein Hash bestätigt Integrität,
keine Sicherheitszertifizierung. Der Installer ist noch nicht mit einem
Authenticode-Zertifikat signiert; ein unabhängiger Sicherheitsaudit ist
nicht veröffentlicht.

Remote-Zugriff benötigt derzeit Tailscale und einen aktiven Host.
Windows-Projektbefehle sind deaktiviert. Modellzugang und mögliche API-Kosten
hängen von den jeweiligen Nutzerkonten ab. Diese Grenzen gehören zur
Beschreibung der Alpha und bleiben öffentlich nachvollziehbar.
