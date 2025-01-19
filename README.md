
## Inhalt der Repository

Das Repository `allgemeinbildung-prompts/olat/` enthält verschiedene Markdown-Dateien, die unterschiedliche Fragetypen und Schwierigkeitsgrade basierend auf der Bloom-Taxonomie abdecken. Jeder Fragetyp ist in einer separaten Datei organisiert, um die Navigation und Nutzung zu erleichtern.

### Verfügbare Fragetypen

- **Drag & Drop (`draganddrop.md`)**
- **GPTs (`gpts.md`)**
- **Inline Fill-in-the-Blanks (`inline_fib.md`)**
- **KPRIM (`kprim.md`)**
- **Multiple Choice 1 (`multiple_choice1.md`)**
- **Multiple Choice 2 (`multiple_choice2.md`)**
- **Multiple Choice 3 (`multiple_choice3.md`)**
- **Single Choice (`single_choice.md`)**
- **True/False (`truefalse.md`)**

## So verwendest du die Prompts

1. **Navigiere zum gewünschten Fragetyp:**
   - Öffne das Verzeichnis `olat/` und wähle die entsprechende Markdown-Datei für den gewünschten Fragetyp (z.B. `draganddrop.md`).

2. **Kopiere den Prompt:**
   - Klicke auf die ausgewählte Datei, um ihren Inhalt anzuzeigen.
   - Suche den Codeblock, der den Prompt enthält.
   - Klicke auf die "Copy"-Schaltfläche oben rechts im Codeblock, um den Inhalt in die Zwischenablage zu kopieren.

3. **Einfügen und Verwenden:**
   - Füge den kopierten Prompt in deine gewünschte Anwendung oder dein Dokument ein und nutze ihn nach Bedarf.

## Beispielprompt

Hier ist ein Beispiel aus der Datei `draganddrop.md`:

```json
{
  "Typ": "Drag&Drop",
  "Level": "Verstehen",
  "Title": "Antragsdelikt vs. Offizialdelikt",
  "Question": "Ordnen Sie die Deliktarten den richtigen Erklärungen zu.",
  "Points": 2,
  "Categories": {
    "Antragsdelikt": ["Diebstahl zum Nachteil eines Angehörigen"],
    "Offizialdelikt": ["Mord"]
  }
}
