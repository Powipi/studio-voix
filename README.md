# Studio voix

Une page web pour enregistrer une voix off **plan par plan** sur une préversion vidéo, directement dans le navigateur (Chrome, Edge ou Firefox, sur ordinateur).

- On ouvre la page, puis on y charge deux fichiers : la fiche des plans (`studio-voix.md`) et la vidéo de la préversion. (Un lien qui porte les plans dans son ancre `#p=…` marche aussi.)
- Les fichiers restent sur l'ordinateur : ils ne sont envoyés nulle part.
- Pour chaque plan : décompte, lecture de la vidéo depuis le début du plan, enregistrement du micro, arrêt automatique en fin de plan. Autant d'essais que voulu, avec un compteur d'essais et de minutes ; réécoute avec l'image.
- Export d'un `.zip` : `voix.wav` (plans gardés, calés sur la préversion), un `.wav` par plan et `calage.json`.

Aucun compte, aucun serveur, aucune donnée stockée en ligne : les essais restent dans le navigateur.

En ligne : https://powipi.github.io/studio-voix/
