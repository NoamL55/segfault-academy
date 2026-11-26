# Segfault Academy

Mini-jeux pour apprendre le langage C notion par notion : pointeurs, chaînes, allocation dynamique, fichiers, structures, modules et généricité.

Le site tient dans un seul fichier, `index.html`. Il n'a besoin d'aucune installation ni d'aucun serveur.

**Jouer en ligne, depuis n'importe quel appareil :** https://noaml55.github.io/segfault-academy/

## Jouer sur un ordinateur

Double-clique sur `index.html` : il s'ouvre dans ton navigateur.

## Jouer sur un téléphone ou un autre appareil

Les téléphones n'ouvrent pas facilement un fichier local. Le plus simple est de lancer un petit serveur sur un ordinateur, puis d'ouvrir son adresse depuis l'autre appareil.

Sur l'ordinateur, dans le dossier du projet :

```
python -m http.server 8080
```

Sur l'autre appareil, connecté au même Wi-Fi ou au même réseau Tailscale, ouvre :

```
http://NOM-OU-ADRESSE-DE-L-ORDINATEUR:8080
```

Avec Tailscale, le nom de la machine suffit, par exemple `http://la-bete-de-noam:8080`.

## À savoir

- La progression est enregistrée dans le navigateur de chaque appareil. Elle ne se synchronise pas entre les appareils.
- Les polices viennent de Google Fonts. Sans connexion Internet, le site utilise les polices de l'appareil et fonctionne normalement.
- Le bouton « Copier pour une IA » copie l'énoncé avec une consigne qui demande des indices plutôt que la réponse.
