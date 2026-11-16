# Stock MELEC

Application web installable pour gérer l’inventaire du matériel d’électricité domestique d’une classe de Seconde MELEC.

## Fonctions

- Ajouter des références, choisir une catégorie et une unité, puis définir la quantité comptée et le seuil d’alerte.
- Rechercher et filtrer l’inventaire; mettre à jour une quantité ou supprimer une référence.
- Signaler un matériel manquant ou abîmé, ajouter une note et marquer le signalement comme résolu.
- Parcourir un catalogue de 34 matériels courants de l’installation domestique et ajouter les références utiles à l’inventaire.
- Afficher les logos de l’Académie de Créteil et du lycée polyvalent Lucie Aubrac de Pantin sur l’accueil.
- Exporter l’inventaire en CSV, compatible avec un tableur.
- Conserver les données sur l’appareil et ouvrir l’application hors connexion après son premier chargement.

## Démarrage

Pour essayer l’interface, ouvrez `index.html` dans un navigateur. Pour installer l’application et bénéficier du mode hors connexion, publiez les fichiers sur un hébergement HTTPS statique. Les services workers et l’installation PWA demandent HTTPS (ou localhost).

- **Android :** ouvrez l’adresse HTTPS dans Chrome et choisissez « Installer l’application » ou « Ajouter à l’écran d’accueil ».
- **iPhone/iPad :** ouvrez l’adresse dans Safari, touchez Partager, puis « Sur l’écran d’accueil ».

## Données

L’inventaire est enregistré dans le stockage local du navigateur (`localStorage`). Il ne se synchronise pas entre appareils et n’est pas partagé avec les autres élèves. L’export CSV permet de sauvegarder les quantités; les signalements ne sont pas inclus dans cet export. « Effacer les données locales » supprime définitivement les références et signalements de l’appareil courant.

