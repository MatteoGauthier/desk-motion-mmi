# Blender render instruction

Pour Nathan.

## Installation

1. Installer blender
2. Ajouter blender au PATH pour pouvoir y accéder dans un terminal

## Rendu

Cloner le repo
```bash
git clone https://github.com/MatteoGauthier/desk-motion-mmi.git
```

Démarrer le rendu
```bash
blender -b Desk.blend -o <chemin complet du rendu> -s 125 -e 200 -a
```

*example*
```bash
blender -b Desk.blend -o ./Output -s 125 -e 200 -a

=> C:/Output/0012.png
```
