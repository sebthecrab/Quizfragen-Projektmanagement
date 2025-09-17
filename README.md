
<!DOCTYPE html>

<html lang="de">
<head>
<meta charset="utf-8"/>
<title>Fragenkatalog mit Antworten</title>
<meta content="width=device-width, initial-scale=1" name="viewport"/>
<link rel="icon" href="data:,">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet"/>
<style>
    body { background-color: #f8f9fa; }
    .question { margin-bottom: 2rem; padding: 1.5rem; background-color: #ffffff; border: 1px solid #dee2e6; border-radius: .5rem; box-shadow: 0 0.125rem 0.25rem rgba(0,0,0,.075); }
    .form-check { margin-left: 1rem; }
    .form-check-input:disabled:checked { background-color: #198754; border-color: #198754; }
  </style>
<style>
  .label-correct {
    background-color: #d4edda !important;
    border: 1px solid #198754 !important;
    border-radius: .3rem;
    padding: 0.25rem 0.5rem;
    display: block;
  }
  .label-wrong {
    background-color: #f8d7da !important;
    border: 1px solid #dc3545 !important;
    border-radius: .3rem;
    padding: 0.25rem 0.5rem;
    display: block;
  }
</style>
<style>
  @media print {
    @page {
      size: A4 landscape;
      margin: 1cm;
    }
    body {
      font-size: 9pt;
    }
    table {
      font-size: 8pt;
    }
    table td, table th {
      padding: 3px;
      vertical-align: top;
    }
    h2 {
      font-size: 12pt;
    }
    button {
      display: none !important;
    }
  }
</style>
</head>
<body class="container py-4">
<h1 class="mb-4 text-center">Fragenkatalog für Basis-Zertifizierung im Projektmanagement</h1>
<div class="alert alert-info mb-4">
<h5 class="alert-heading">📘 Anleitung zur Nutzung des Fragenkatalogs</h5>
<ul class="mb-0">
<li><strong>Antworten prüfen</strong>: Überprüft deine ausgewählten Antworten. Richtige und falsche Auswahlfelder werden farblich markiert.</li>
<li><strong>Alle Antworten zurücksetzen</strong>: Setzt alle gesetzten Häkchen zurück, ohne die Seite neu zu laden.</li>
<li><strong>Seite neu laden</strong>: Lädt die Seite vollständig neu. Dies zeigt wieder alle Musterlösungen zur besseren Lernkontrolle.</li>
</ul>
</div>
<div class="text-center mb-4">
<button class="btn btn-success me-2" onclick="evaluateAnswers()">Antworten prüfen</button>
<button class="btn btn-danger me-2" onclick="uncheckAll()">Alle Antworten zurücksetzen</button>
<button class="btn btn-secondary" onclick="window.location.reload()">Seite neu laden</button>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>1. Was ist ein Projekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine wiederholbare Tätigkeit mit definiertem Ergebnis</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine einmalige Aufgabe mit definiertem Anfang und Ende</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine dauerhafte Routineaufgabe</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine Tätigkeit ohne Ziel</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>2. Welche Merkmale kennzeichnen ein Projekt?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Einmaligkeit</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Zielorientierung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Zeitliche Befristung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Standardisierte Prozesse</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>3. Was gehört nicht zu den klassischen Projektphasen?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektstart</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Routinephase</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektabschluss</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektplanung</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>4. Welches Ziel verfolgt Projektmanagement?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Effiziente und zielgerichtete Umsetzung von Projekten</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Erhöhung der Unternehmensgewinne durch Standardisierung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Minimierung von Personalaufwand in der Linie</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Verbesserung der Produktqualität im Tagesgeschäft</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>5. Welche Aussage trifft auf ein Projektziel zu?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Es beschreibt den gewünschten Endzustand des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es definiert die Anzahl der Mitarbeitenden</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es dient ausschließlich der Motivation</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es ist unveränderlich</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>6. Wer trägt die Gesamtverantwortung für das Projekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Auftraggeber</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Projektmitarbeitenden</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Der Projektleiter</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Linienvorgesetzte</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>7. Welches Instrument dient der Visualisierung von Projektabläufen?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Netzplan</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Brainstorming</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> SWOT-Analyse</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektstrukturbaum</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>8. Welche Rolle hat der Auftraggeber im Projekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Er gibt das Projekt in Auftrag und trifft grundlegende Entscheidungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Er arbeitet operativ im Projekt mit</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Er schreibt die Projektziele vor</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Er ist Teil des Projektteams</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>9. Was ist ein Meilenstein?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Element des Risikomanagements</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Ein wichtiges Zwischenergebnis im Projektverlauf</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Planungsdokument</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine Ressourcenzuteilung</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>10. Was beschreibt der Projektstrukturplan (PSP)?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Die hierarchische Gliederung aller Projektaufgaben</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Kosten des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Personalverfügbarkeit</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Den zeitlichen Ablauf des Projekts</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>11. Was ist ein Stakeholder?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine Person oder Gruppe mit Interesse oder Einfluss auf das Projekt</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur die Projektleitung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur der Projektauftraggeber</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur externe Partner</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>12. Welche Methode dient der Stakeholderanalyse?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> SWOT-Analyse</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ishikawa-Diagramm</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Einfluss-Interesse-Matrix</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Netzplantechnik</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>13. Welche Aussage zur SMART-Formel ist korrekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Sie hilft bei der Formulierung von Zielen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie dient zur Teamführung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie ist ein Risikomanagement-Instrument</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie bezieht sich auf das Projektbudget</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>14. Was steht im Projektauftrag?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur die Projektlaufzeit</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur die Kostenplanung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur die Risiken</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Ziele, Umfang, Budget und Zeitrahmen des Projekts</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>15. Wer genehmigt den Projektauftrag?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Der Auftraggeber</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Projektleiter</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Teammitglieder</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Linienvorgesetzte</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>16. Welche Planungsmethode berücksichtigt Pufferzeiten?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektstrukturplan</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Risikoanalyse</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Netzplan</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ressourcenliste</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>17. Was ist kein Vorteil der Projektplanung?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Garantierte Zielerreichung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Früherkennung von Engpässen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ressourcenkontrolle</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Strukturierung von Aufgaben</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>18. Welche Dimension gehört zur magischen Dreieck des Projektmanagements?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Zeit</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Motivation</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Kosten</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Qualität</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>19. Was beschreibt ein Arbeitspaket?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Projektziel</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine klar definierte Aufgabe mit Verantwortlichem, Aufwand und Ergebnis</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Stakeholderinteresse</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Phasenmodell</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>20. Was ist ein Risiko im Projektmanagement?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein geplanter Meilenstein</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine Ressource</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Ein potenzielles Ereignis mit negativer Auswirkung auf das Projekt</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Ziel</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>21. Was beschreibt eine Projektorganisation?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Verwaltung der Unternehmensstruktur</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Das Marketing des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Finanzierung des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Die Strukturierung von Zuständigkeiten und Rollen im Projekt</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>22. Welche Aussage zur Linien-Projektorganisation ist korrekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Der Projektleiter hat geringe Entscheidungskompetenz</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Projektleiter ist allein verantwortlich</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es gibt keine Vorgesetzten außerhalb des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie ist unabhängig von der Unternehmensstruktur</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>23. Was ist typisch für eine Matrix-Projektorganisation?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Mitarbeitende berichten an Linien- und Projektleitung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Projektleitung ist alleiniger Vorgesetzter</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es gibt keine Konflikte</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Projektmitarbeiter sind ausschließlich dem Projekt zugeordnet</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>24. Was sind Vorteile interdisziplinärer Teams?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Vielfältige Kompetenzen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eindeutige Führungsstruktur</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Kürzere Kommunikationswege</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Höhere Kreativität</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>25. Was ist ein Team-Kickoff-Meeting?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Abschlussmeeting</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Personalgespräch</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Feedbackrunde</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Erstes gemeinsames Treffen des Projektteams zur Zielklärung</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>26. Was ist ein Projektteam?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine Gruppe von Personen, die gemeinsam ein Projektziel verfolgen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Geschäftsführung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Marketingabteilung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Gremium zur Projektabnahme</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>27. Was fördert die Motivation im Projektteam?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Unklare Aufgabenverteilung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Transparente Kommunikation</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Anerkennung von Leistung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Mikromanagement</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>28. Was ist bei der Teamarbeit in Projekten wichtig?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Klare Rollenverteilung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Regelmäßige Abstimmungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Möglichst wenig Kommunikation</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Strikte Hierarchien</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>29. Was ist ein Stakeholder-Management-Plan?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektkostenplan</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Kommunikationsplan für das Team</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Plan zur Identifikation und Einbindung wichtiger Interessengruppen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Dokumentenablage</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>30. Was hilft bei Konflikten im Projektteam?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Offene Kommunikation und Moderation</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ignorieren des Problems</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Hierarchisches Durchsetzen von Entscheidungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Informationsverweigerung</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>31. Was ist ein Gantt-Diagramm?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine Balkenplanung zur Darstellung von Aufgaben über Zeit</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Organigramm</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine Methode zur Risikoanalyse</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine Liste von Stakeholdern</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>32. Wozu dient ein Netzplan?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Berechnung von Budgets</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Mitarbeiterverwaltung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Darstellung von Konflikten</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Analyse logischer Abhängigkeiten zwischen Aufgaben</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>33. Was ist eine Ressource im Projekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Alles, was für die Projektdurchführung benötigt wird</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur das Projektbudget</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur der Projektleiter</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Nur die Technik</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>34. Welche Aussage zu Ressourcen ist korrekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ressourcenplanung ist optional</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ressourcen werden nur bei Projektende benötigt</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Ressourcen können materiell oder personell sein</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ressourcen sind unendlich verfügbar</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>35. Welche Kostenart gehört zu den Projektkosten?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Sachkosten</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Steuern des Unternehmens</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Personalkosten</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Aktienkurs</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>36. Was beschreibt die Projektlaufzeit?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Zeit von Projektstart bis -abschluss</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Zeit zwischen zwei Teambesprechungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Die Lebensdauer des Produkts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der Garantiezeitraum</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>37. Was ist ein kritischer Pfad im Netzplan?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Der kürzeste Weg im Plan</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein optionaler Ablauf</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Backup-Plan</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Der längste Weg ohne zeitlichen Puffer</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>38. Warum ist Kostenkontrolle im Projekt wichtig?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Um Teamkonflikte zu reduzieren</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Um Budgetüberschreitungen zu vermeiden</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Um mehr Mitarbeiter einstellen zu können</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Um Lieferanten zu kontrollieren</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>39. Was ist eine Aufwandsschätzung?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Berechnung der Stakeholderanzahl</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Bewertung von Risiken</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Prognose des notwendigen Arbeitsaufwands für eine Aufgabe</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Analyse der Teamdynamik</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>40. Was ist das Ziel der Terminplanung?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Vermeidung aller Meetings</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Maximale Auslastung der Ressourcen</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Rechtzeitige Fertigstellung des Projekts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Vermeidung der Stakeholderkommunikation</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>41. Was ist ein Kommunikationsplan?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Plan zur Regelung von Informationswegen im Projekt</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ablaufplan für Kundenbesuche</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Budgetübersicht</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Personalakte</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>42. Was gehört zur Projektkommunikation?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektarchiv</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> SWOT-Analyse</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Regelmäßige Meetings</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Statusberichte</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>43. Welche Methode unterstützt die Risikoanalyse?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Risikomatrix</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> PSP</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Gantt-Diagramm</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Kommunikationsplan</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>44. Was ist ein Projektrisiko?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein fixer Bestandteil des Zeitplans</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Eine garantierte Störung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Eine potenzielle Störung des Projektablaufs</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein definierter Projektschritt</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>45. Wie geht man mit Risiken um?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Identifizieren</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ignorieren</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Bewerten</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Maßnahmen planen</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>46. Was ist ein Änderungsmanagement?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Plan zur Erhöhung der Projektkosten</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Liste aller Teammitglieder</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Prozess zur Bewertung und Umsetzung von Änderungen im Projekt</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Kommunikationsprotokoll</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>47. Was ist ein Change Request?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Ticket für die Projektabnahme</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Meilenstein</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Ein Planungsdokument</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Ein Antrag auf Änderung im Projekt</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>48. Was ist bei Änderungen wichtig?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Bewertung der Auswirkungen</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Dokumentation</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sofortige Umsetzung ohne Prüfung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projektziel ignorieren</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>49. Was ist ein Projektstatusbericht?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Abschlussbericht</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Regelmäßige Zusammenfassung des Projektfortschritts</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Lebenslauf des Projektleiters</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Vertragsentwurf</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>50. Was zeigt ein Ampelstatus im Projekt?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Den aktuellen Stand anhand von Farben (z. B. grün, gelb, rot)</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Verkehrssituation rund um das Büro</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Wetterlage am Standort</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Urlaubstage im Team</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>51. Was ist Ziel der Projektabschlussphase?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Planung neuer Projekte</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Geordneter Projektabschluss und Übergabe der Ergebnisse</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Personaleinsatzplanung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Urlaubsverwaltung</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>52. Was gehört zu einem Abschlussbericht?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Lebenslauf des Projektleiters</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Projektergebnisse</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Erfüllungsgrad der Ziele</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Erfahrungen und Lessons Learned</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>53. Was bedeutet 'Lessons Learned'?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Rückblick auf Erfolge und Fehler zur Verbesserung künftiger Projekte</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Schulung neuer Mitarbeitender</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Genehmigung der Projektziele</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Budgeterhöhung</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>54. Was ist Qualität im Projektmanagement?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Geschwindigkeit der Umsetzung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Zufriedenheit des Projektleiters</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Grad der Zielerfüllung bezogen auf definierte Anforderungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Anzahl der Teammitglieder</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>55. Welche Maßnahmen sichern die Qualität?</strong><br/>
<div class="text-info mb-2">💡 Mehrere Antworten möglich</div><div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Abnahmetests</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Informationsverweigerung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Änderungsvermeidung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Qualitätskontrollen</label></div>
</div>
<div class="question" data-topic="Technische Kompetenzen (Practice)">
<strong>56. Was beschreibt das magische Dreieck im PM?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Zielkonflikt zwischen Zeit, Kosten und Qualität</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Drei Projektleiter pro Projekt</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Drei Kundengruppen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Drei Phasen der Teamentwicklung</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>57. Warum ist Ethik im Projektmanagement wichtig?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Für die Einhaltung des Budgets</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Zur Projektverzögerung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Zur Gewinnerhöhung</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Für vertrauensvolle und faire Zusammenarbeit</label></div>
</div>
<div class="question" data-topic="Verhaltenskompetenzen (People)">
<strong>58. Welche Rolle spielt Transparenz?</strong><br/>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Sie stärkt das Vertrauen und ermöglicht fundierte Entscheidungen</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie reduziert Projektziele</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie ersetzt Planung</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Sie erschwert die Kommunikation</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>59. Was ist der Unterschied zwischen Projekt und Linie?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Projekt hat keine Ziele</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Linie ist nur für Projekte zuständig</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Projekt ist zeitlich befristet, Linie ist dauerhaft</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Es gibt keinen Unterschied</label></div>
</div>
<div class="question" data-topic="Kontextkompetenzen (Perspective)">
<strong>60. Was hilft, ein Projekt erfolgreich abzuschließen?</strong><br/>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Unklare Ziele</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Spontane Teamwahl</label></div>
<div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox"/> Verzicht auf Statusberichte</label></div>
<div class="form-check"><label class="form-check-label"><input checked="" class="form-check-input" type="checkbox"/> Sorgfältige Planung und Kommunikation</label></div>
</div>
<div class="text-center mb-4">
<button class="btn btn-success me-2" onclick="evaluateAnswers()">Antworten prüfen</button>
<button class="btn btn-danger me-2" onclick="uncheckAll()">Alle Antworten zurücksetzen</button>
<button class="btn btn-secondary" onclick="window.location.reload()">Seite neu laden</button>
</div>
<div class="mt-4 mb-5 text-end">
<!--<button class="btn btn-outline-secondary" onclick="printEvaluation()">
    🖨️ Auswertung drucken
  </button>-->
</div>
<script>
  function printEvaluation() {
    const content = document.getElementById("result")?.innerHTML || "";
    const chartCanvas = document.getElementById("icbChart");

    const w = window.open("", "", "width=1000,height=800");
    w.document.write('<html><head><title>Auswertung drucken</title>');
    w.document.write("<link href='https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css' rel='stylesheet'>");
    w.document.write("</head><body class='p-4'>");
    w.document.write("<h2>📊 Deine Auswertung</h2>");
    w.document.write(content);

    // Canvas als Bild einfügen (falls vorhanden)
    if (chartCanvas) {
      const img = chartCanvas.toDataURL();
      w.document.write("<h4 class='mt-5'>Diagramm</h4>");
      w.document.write(`<img src="${img}" style="max-width:100%;">`);
    }

    w.document.write("</body></html>");
    w.document.close();
    w.focus();
    w.print();
    w.close();
  }
</script>

<script>
  function uncheckAll() {
    const checkboxes = document.querySelectorAll('input[type="checkbox"]');
    checkboxes.forEach(cb => cb.checked = false);

    const labels = document.querySelectorAll('label');
    labels.forEach(label => label.classList.remove("label-correct", "label-wrong"));

    const questions = document.querySelectorAll('.question');
    questions.forEach(q => q.classList.remove("border-success", "border-danger"));

    const infoBtns = document.querySelectorAll(".info-btn");
    infoBtns.forEach(btn => btn.classList.add("d-none"));
  }
</script>

<script>
  function evaluateAnswers() {
    let total = 0;
    let correct = 0;
    const questions = document.querySelectorAll('.question');
    const topicStats = {};

    questions.forEach((q, idx) => {
      const topic = q.dataset.topic || "Unbekannt";
      const questionText = q.querySelector('strong')?.innerText.trim() || "Frage " + (idx + 1);
      
      topicStats[topic] = topicStats[topic] || { total: 0, correct: 0, questions: [] };
      topicStats[topic].total++;
      total++;

      let isCorrect = true;
      const correctAndSelected = [];
      const wrongSelected = [];
      const missingCorrect = [];

      const labels = q.querySelectorAll("label");

      labels.forEach(label => {
        label.classList.remove("label-correct", "label-wrong");
        const cb = label.querySelector('input[type="checkbox"]');
        const text = label.textContent.trim();
        const isSolutionChecked = cb.outerHTML.includes('checked');
        const isUserChecked = cb.checked;

        if (isSolutionChecked && isUserChecked) {
          correctAndSelected.push(text);
          label.classList.add("label-correct");
        }
        if (isSolutionChecked && !isUserChecked) {
          missingCorrect.push(text);
          label.classList.add("label-wrong");
          isCorrect = false;
        }
        if (!isSolutionChecked && isUserChecked) {
          wrongSelected.push(text);
          label.classList.add("label-wrong");
          isCorrect = false;
        }
      });

      topicStats[topic].questions.push({
        text: questionText,
        correct: isCorrect,
        correctAnswers: correctAndSelected.length > 0 ? correctAndSelected.map(a => `✔️ ${a}`).join("<br>") : "-",
        wrongAnswers: wrongSelected.length > 0 ? wrongSelected.map(a => `❌ ${a}`).join("<br>") : "-",
        missingAnswers: missingCorrect.length > 0 ? missingCorrect.map(a => `⚠️ ${a}`).join("<br>") : "-"
      });

      if (isCorrect) {
        q.classList.remove("border-danger");
        q.classList.add("border-success");
        correct++;
        topicStats[topic].correct++;
      } else {
        q.classList.remove("border-success");
        q.classList.add("border-danger");
      }
    });

    // Bestehensprüfung
    let passed = true;
    for (const [topic, stat] of Object.entries(topicStats)) {
      const quote = stat.total > 0 ? (stat.correct / stat.total) : 0;
      if (quote < 0.5) {
        passed = false;
        break;
      }
    }

    const percent = Math.round((correct / total) * 100);
    const resultText = passed 
      ? "<div class='alert alert-success'><strong>✔️ Bestanden:</strong> Sie haben in allen Kompetenzfeldern mindestens 50 % erreicht.</div>"
      : "<div class='alert alert-danger'><strong>❌ Nicht bestanden:</strong> Sie haben in mindestens einem Kompetenzfeld unter 50 % erreicht.</div>";

    let html = `<html><head>
      <title>Auswertung</title>
      <link href='https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css' rel='stylesheet'>
      <meta charset='utf-8'>
      <style>
        .progress { height: 20px; }
        .progress-bar { font-size: 12px; line-height: 20px; }
      </style>
      </head><body class='p-4'>
      <div class='d-flex justify-content-end mb-3'>
        <button onclick='window.print()' class='btn btn-outline-secondary'>🖨️ Seite drucken</button>
      </div>
      <h2>Deine Ergebnisse</h2>
      ${resultText}
      <p><strong>✔️ Sie haben ${correct} von ${total} Fragen richtig beantwortet (${percent}%)</strong></p>`;

    // Zusammenfassung
    
    html += `<div class="mb-4">`;
    for (const [topic, stat] of Object.entries(topicStats)) {
      const pct = stat.total > 0 ? Math.round((stat.correct / stat.total) * 100) : 0;
      html += `<div class="mb-1"><strong>${topic}</strong> (${pct}%)</div>
      <div class="progress mb-3">
        <div class="progress-bar bg-success" style="width: ${pct}%">${pct}%</div>
      </div>`;
    }
    html += `</div>`;

    for (const [topic, stat] of Object.entries(topicStats)) {
      const catTotal = stat.total;
      const catCorrect = stat.correct;
      const catPercent = catTotal > 0 ? Math.round((catCorrect / catTotal) * 100) : 0;
      html += `<h4 class='mt-4'>${topic} – ${catCorrect} von ${catTotal} korrekt (${catPercent}%)</h4>`;
      html += `<table class="table table-bordered table-sm">
        <thead><tr>
          <th>Frage</th>
          <th>Richtige Antwort(en)</th>
          <th>Falsch ausgewählt</th>
          <th>Fehlend (nicht ausgewählt)</th>
        </tr></thead><tbody>`;

      stat.questions.forEach(q => {
        html += `<tr>
          <td>${q.text}</td>
          <td>${q.correctAnswers}</td>
          <td>${q.correct ? "-" : q.wrongAnswers}</td>
          <td>${q.correct ? "-" : q.missingAnswers}</td>
        </tr>`;
      });

      html += "</tbody></table>";
    }

    html += "</body></html>";

    const w = window.open("", "_blank", "width=1000,height=800");
    w.document.write(html);
    w.document.close();
    w.focus();
  }
</script>
</body>
</html>
