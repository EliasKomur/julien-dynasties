# Julien & Dynasties

Simulation de guilde d'aventuriers dans le comté d'Aurmont. Vous dirigez une guilde de la Ligue des Lanternes : recrutez, équipez, envoyez quatre héros en donjon chaque semaine, et vivez avec ce qui remonte. Les morts sont définitives, les Annales retiennent tout.

Projet personnel, non commercial. Univers, noms et textes originaux.

## Jouer

Ouvrez `index.html` dans un navigateur (Chrome, Edge, Firefox). Aucune installation, aucun serveur.
La partie est sauvegardée automatiquement dans le navigateur. L'onglet Options donne un code de sauvegarde pour changer d'appareil.

## Contenu

- Ligue de 32 guildes sur 4 divisions (Ardoise, Bronze, Argent, Couronne), 14 semaines par saison, montées et descentes, la Lanterne d'Or pour le champion.
- Coupe du Solstice : 32 guildes, élimination directe, 5 tours.
- Descentes en donjon simulées passe par passe : conditions (Gel, Brume, Éboulis, Spores), salles à événements, gardiens avec mécaniques propres.
- Héros : 6 classes, 16 traits actifs en combat, niveaux, séquelles, hauts faits, amitiés, parenté avec les héros tombés, vieillissement, retraite.
- Mort permanente, tactiques Prudente / Équilibrée / Agressive, infirmerie et salle d'armes.
- Mécène avec un objectif par saison, contrats à renouveler ou négocier.
- Quêtes hors des donjons, marché des transferts et offres des guildes rivales, derbys entre guildes de la même ville.
- Carte du comté générée pour chaque partie.
- Annales écrites à partir des événements réels de la partie, mémorial avec épitaphes, records de la maison, Gazette, Codex.
- Mode Ironman, musique synthétisée, thème clair ou sombre.

## Mettre en ligne (GitHub EliasKomur + Vercel)

1. Sur GitHub (compte EliasKomur), créez un dépôt public ou privé nommé `julien-dynasties`.
2. Dans le dossier décompressé, ouvrez un terminal (VS Code : Terminal > Nouveau terminal) et lancez :

```bash
git init
git add .
git commit -m "Julien & Dynasties"
git branch -M main
git remote add origin https://github.com/EliasKomur/julien-dynasties.git
git push -u origin main
```

3. Sur vercel.com : Add New > Project > importez `julien-dynasties`.
   Framework Preset : **Other**. Laissez Build Command et Output Directory vides. Deploy.
4. Le jeu est en ligne sur `julien-dynasties.vercel.app` (ou un nom proche si celui-ci est pris).
