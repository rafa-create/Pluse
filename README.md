# PULSE — Le Dragon des Cieux

Jeu web solo (style Geometry Dash / grotte bioluminescente).

**Jouer (web) :** https://rafa-create.github.io/Pluse/

## Contrôles

Maintiens n’importe où (ou Espace) pour monter, relâche pour plonger.

## Publication — iOS d’abord (plus rapide)

Sur un compte perso Google Play, la prod exige souvent **12 testeurs / ~14 jours**.  
Sur l’**App Store**, tu peux envoyer en review Apple directement avec ton compte déjà actif (BeatOnStep).

### Sur un Mac

```bash
npm install
npm run sync
npm run open:ios
```

Dans Xcode : équipe de signing = ton Apple Developer → Archive → Distribute App → App Store Connect → Submit for Review.

### Android (plus tard)

```bash
npm run open:android
```

Puis test fermé Play si ton compte l’exige, avant la prod.
