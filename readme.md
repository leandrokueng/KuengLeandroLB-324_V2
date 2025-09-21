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

### LB 324 – Aufgabe 4: Deployment auf Azure

In dieser Aufgabe wird das Tagebuch-Projekt in der Cloud (Microsoft Azure) veröffentlicht.  
Dazu wurden die notwendigen **Geheimnisse (Secrets)** wie Passwörter sicher hinterlegt und ein automatisierter Deployment-Workflow eingerichtet.  

---

### 1. Geheimnisse mit `.env`-Datei

Lokal wurde eine **`.env`-Datei** erstellt, um geheime Zugangsdaten wie Passwörter nicht direkt im Code zu speichern.  
Beispielinhalt:
<img width="2048" height="1189" alt="image" src="https://github.com/user-attachments/assets/531d555b-44ae-4251-bd31-b66850b211ef" />
<img width="2048" height="1280" alt="image" src="https://github.com/user-attachments/assets/e34575a2-ac69-4b94-98a5-ecc51a11b1d5" />



```env
 PASSWORD=MaxMuster_TheProGrammer*

Link: kueng-lb324-v2-ccdgedd2f5gdchgh.germanywestcentral-01.azurewebsites.net

