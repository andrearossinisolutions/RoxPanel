# RoxPanel — releases

Pacchetti pronti all'uso di **RoxPanel** per Windows (exe) e il file `latest.json` che l'app legge per sapere se esiste una versione più nuova.

RoxPanel è il programma che collega le periferiche fisiche (la prima è FCUpi, il pannello FCU per l'Airbus A320) al simulatore. Il codice sorgente non è in questa repo: qui vivono solo le release.

## Scaricare
Vai nella sezione **Releases** e scarica l'ultimo pacchetto `RoxPanel-X.Y.Z.zip`, estrailo e avvia `RoxPanel.exe`.

## Come si pubblica una versione (maintainer)
1. Compila l'exe dal sorgente (`build.bat`) e annota lo SHA-256 del pacchetto.
2. Crea la release con il pacchetto allegato (tag `vX.Y.Z`).
3. Aggiorna `latest.json` (versione, note, hash) e fai il commit.
