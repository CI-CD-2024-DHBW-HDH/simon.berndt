# Klausur 2023 DHBW HDH

## Setup

### Klone dieses Repository

1. Klone das Repository
   ```bash
   git clone <TODO repo url>
   cd klausur
   git remote remove origin
   ```
2. Erstelle in der GitHub Organisation ein Repository mit dem Namen **\<vorname>.\<nachname>**
3. Lade den Stand in das Repository hoch
   ```bash
   git remote add origin <url deines Repositories>
   git push -u origin master
   ```
4. Erstelle einen Branch für die Bearbeitung
   > Vergesse am Ende nicht deine Bearbeitung hochzuladen

### Sicherstellen, dass alles geht

Führe folgende Befehle in deinem Repository aus, um sicherzustellen, dass alles geht:

```bash
npm install

npm run dev
```

## Aufgaben (20 Punkte)

1. Installiere: **(3 Punkte)**

   - ESLint
   - Jest
   - Prettier
     > Die Config Dateien brauchen nicht angepasst werden

   > Denke auch an die nötigen Typescript dependencies

2. Schreibe ein `Dockerfile`, dass dazu benutzt werden kann, die Seite zur Verfügung zu stellen **(2 Punkte)**
3. Schreibe GitHub Actions für: **(3 Punkte)**
   - Continuous Integration
   - Continuous Delivery (GitHub Packages)
   - Continuous Deployment (GitHub Pages)
4. Definiere alle nötigen Manifeste um das erstellte Image auf einem Kubernetes Cluster zu deployen **(5 Punkte)**
5. Erkläre in eigenen Worten:
   - Welche Vorteile ein Kubernetes Deployment gegenüber einem Kubernetes Pod hat **(2 Punkte)**
   - Wofür ein Kubernetes Service gut ist **(2 Punkte)**
   - Mehrere Wege wie man eine Kubernetes Anwendung von außen erreichen kann **(3 Punkte)**

## Zusatzaufgabe:

Definiere einen Kubernetes Job **(2 Punkte)**
