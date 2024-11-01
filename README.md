# Projekt-Installation

## 1. Repository klonen
Klonen Sie das Repository, indem Sie den folgenden Befehl ausführen:
```bash
git clone https://github.com/IhrBenutzername/docker-nodejs-sample.git
cd docker-nodejs-sample
```

## 2. Installation der notwendigen Pakete
Stellen Sie sicher, dass alle notwendigen Pakete installiert sind, indem Sie den folgenden Befehl ausführen:
```bash
npm install
```

## 3. Docker-Konfiguration und -Installation
Vergewissern Sie sich, dass Docker installiert ist. Befolgen Sie die Installationsanweisungen für Ihr Betriebssystem auf [docs.docker.com](https://docs.docker.com/get-docker/).

Erstellen Sie eine `Dockerfile` und eine `docker-compose.yml` im Projektverzeichnis, falls diese noch nicht vorhanden sind.

## 4. Applikation in einem Docker-Container starten
Starten Sie die Applikation im Docker-Container mit folgendem Befehl:
```bash
docker-compose up
```

Die Anwendung läuft nun in einem Docker-Container und ist unter `http://localhost:3000` erreichbar (abhängig von der Konfiguration).
```
