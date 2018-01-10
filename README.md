# jeedom_mini4kcmd

Ce script permet de piloter, en partie, le player Freebox mini4k

## INSTALLATION  
### Sur votre jeedom  
- `sudo apt install android-tools-adb`

### Sur votre mini4k
- paramètres
- À propos
- Appuyer sur OK 8 fois sur la ligne **Build** (*passage en mode développeur*)
- paramètres
- Option pour les développeurs (*Dernière option de la 2ème ligne*)
- Débogage
- Débogage USB
- Activé

## UTILISATION  

À la première utilisation, une demande d'autorisation va s'afficher sur votre télé.  
- Cocher toujours accepter  

Créer un script  
- "Type script" : Script
- "Type" : Action, Message
- "Requête" : /var/www/html/plugins/script/core/ressources/mini4k_cmd IP_DE_VOTRE_MINI4K #message#

### Commandes acceptées
- ON
- OFF
- XX (*où **XX** est le n° de chaine*)
- MUTE
- VOL+ *X* (*où **X** est une valeur facultative comprise entre 1 et 4*)
- VOL- *X* (*où **X** est une valeur facultative comprise entre 1 et 4*)
- VOL XX (*où **XX** est le niveau sonore entre 0 et 100*)
- PAUSE
- PRG+
- PRG-
- TV

