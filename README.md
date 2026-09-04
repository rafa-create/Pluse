# PULSE — Le Dragon des Cieux

Jeu web solo (style Geometry Dash / grotte bioluminescente).

**Jouer (web) :** https://rafa-create.github.io/Pluse/

## Contrôles

Maintiens n’importe où (ou Espace) pour monter, relâche pour plonger.

## App Android (Capacitor) — chemin rapide

Prérequis : [Android Studio](https://developer.android.com/studio) (embarque le JDK).

```bash
npm install
npm run sync
npm run open:android
```

Dans Android Studio : lance sur un émulateur / téléphone, puis **Build > Generate Signed Bundle / APK** pour le Play Store.

iOS : même projet + `npx cap add ios` sur un Mac, avec ton compte Apple Developer existant.
