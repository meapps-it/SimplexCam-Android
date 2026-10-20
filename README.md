# SimplexCam Android

Repository per lo sviluppo dell'app Android SimplexCam, collegata ai dispositivi EZVIZ/TIM Cam.

## Stato
I sorgenti verranno caricati solo dopo che il repository sarà reso **privato**.

## Compilazione APK di prova
Il workflow `.github/workflows/simplexcam-apk.yml` compila automaticamente lo ZIP `SimplexCam-0.2-beta-Sorgenti.zip` caricato nella radice del repository. Una compilazione riuscita produce un artifact `SimplexCam-0.2-beta-APK` (APK debug, non adatto alla pubblicazione sul Play Store).

Funzioni audio, diretta, registrazioni e allarmi devono essere collaudate sulla TIM Cam reale. Le notifiche push non sono ancora implementate.

**Sicurezza:** non pubblicare token EZVIZ, password, codice di verifica o registrazioni private.
