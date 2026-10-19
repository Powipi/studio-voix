# Studio voix

Une page web pour enregistrer une voix off **plan par plan** sur une préversion vidéo, directement dans le navigateur (Chrome, Edge ou Firefox, sur ordinateur).

- Le lien d'un Reel porte la liste des plans dans son ancre (`#p=…`), qui n'est jamais envoyée au serveur.
- On choisit le fichier vidéo de la préversion sur son ordinateur : il n'est envoyé nulle part.
- Pour chaque plan : décompte, lecture de la vidéo depuis le début du plan, enregistrement du micro, arrêt automatique en fin de plan. 3 essais au maximum par plan, réécoute avec l'image.
- Export d'un `.zip` : `voix.wav` (plans gardés, calés sur la préversion), un `.wav` par plan et `calage.json`.

Aucun compte, aucun serveur, aucune donnée stockée en ligne : les essais restent dans le navigateur.

En ligne : https://powipi.github.io/studio-voix/
