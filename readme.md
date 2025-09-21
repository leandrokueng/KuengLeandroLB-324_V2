# LB 324

## Aufgabe 2

### Pre-commit Hooks (HZ2)

Zur Sicherstellung der Codequalität und der Funktionsfähigkeit werden in diesem Projekt **pre-commit Hooks** eingesetzt.  
Diese laufen automatisch bei jedem `git commit` und `git push` und verhindern so, dass fehlerhafter oder unformatierter Code in das Repository gelangt.

---

### Installation (einmalig)

1. Stelle sicher, dass Python und pip installiert sind.
2. Installiere pre-commit mit:
   ```bash
   pip install pre-commit

3. Installiere die Commit-Hooks:
   ```bash
   pre-commit install

4. Installiere zusätzlich die Push-Hooks
   ```bash
   pre-commit install -t pre-push



## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
