# Site Quarto personnel

Gabarit à personnaliser pour STT-4230 / STT-6230. Les rubriques sont des indications, pas des réalisations déjà accomplies.

## Ouvrir et rendre

1. Sur GitHub, cliquez sur **Use this template → Create a new repository**. Créez un dépôt public dans votre compte, par exemple `site-personnel`. Si vous avez déjà un dépôt pour votre site, continuez à l’utiliser.
2. Clonez votre dépôt et ouvrez `site-personnel.Rproj` dans RStudio.
3. Dans le terminal de RStudio, lancez la commande suivante depuis le dossier qui contient `_quarto.yml`.

```bash
quarto render
```

Ouvrez docs/index.html. Pour voir le site pendant les modifications, vous pouvez utiliser :

```bash
quarto preview
```

Le rendu ne publie rien. Gardez _quarto.yml et les sources à la racine. docs/ ne contient que les sorties générées; ne placez pas de fichiers uniques dans ce dossier.

## Personnaliser

Complétez index.qmd, parcours.qmd, realisations.qmd et declaration-ia.qmd. Remplacez les liens d'exemple par vos adresses ou supprimez les lignes inutiles. Présentez une réalisation issue du portfolio et une du projet ou d'un module avancé. Une justification technique est demandée à tous; celle de STT-6230 est approfondie. Ne publiez aucun contenu confidentiel, énoncé réservé ou corrigé sans autorisation.

## Publier quand votre contenu est prêt

1. Modifiez les fichiers `.qmd` et lancez `quarto render`. Ouvrez `docs/index.html` pour vérifier le résultat.
2. Faites un commit des sources, de `.nojekyll` et de `docs/`, puis poussez le commit vers GitHub.
3. Dans votre dépôt GitHub, choisissez **Settings → Pages → Deploy from a branch → main → /docs → Save**. Si votre branche principale porte un autre nom, sélectionnez-la.
4. Quand le déploiement est terminé, cliquez sur **Visit site** dans **Settings → Pages** et vérifiez la navigation.

Quarto génère les fichiers HTML dans `docs/` et y copie `.nojekyll`. GitHub Pages publie le contenu de `docs/` qui a été poussé sur GitHub.

Pour mettre le site à jour, modifiez les sources, relancez `quarto render`, puis faites un nouveau commit et un push, en incluant le dossier `docs/`.

## Remise finale

Mercredi 16 décembre 2026 à 23 h 55, selon les consignes du cours. Indiquez dans ce README les liens du site et du dépôt source, le commit à évaluer et les emplacements des deux réalisations. Ajoutez le lien du site dans votre portfolio et indiquez la trace reprise. Déclarez les usages significatifs de l'IA conformément à la page du cours.

Consignes : https://aureliennicosiaulaval.github.io/programmation-pour-la-science-des-donnees/site-personnel.html
