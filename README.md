# ESA — Projet de stationnement automatisé — 243-557 A2026

Dépôt de départ commun aux cinq équipes. Chaque équipe travaille dans son propre dépôt créé à partir de ce modèle.

## Démarrage
1. Sur GitHub, créer un dépôt d’équipe à partir du modèle (**Use this template**).
2. Inviter les membres de l’équipe comme collaborateurs.
3. Cloner le dépôt de l’équipe avec `git clone <URL_DU_DEPOT_EQUIPE>`.
4. Lire `docs/` avant de commencer.
5. Développer les modules dans les dossiers prévus, sans remplacer les fichiers des autres étudiants.

## Organisation
- `rpi/` : application Raspberry Pi, PyQt et communications.
- `stm32_borne/` : capteur de luminosité, impression et éclairage.
- `stm32_bas/` : capteurs IR et DEL.
- `stm32_haut/` : moteurs, capteurs de niveau et IR.
- `pc_supervision/` : application de supervision MQTT.
- `tests/` : essais et simulateurs.
- `docs/` : spécifications communes et interfaces.

## Règles minimales
- Respecter les identifiants et formats du protocole CAN.
- Chaque étudiant documente et teste ses fonctionnalités.
- Ne pas créer de seconde application principale PyQt ou de seconde initialisation CAN sur le même contrôleur.
- Ne pas déposer de secrets, mots de passe ou données personnelles dans Git.

**Note :** les dossiers sont volontairement vides. Les étudiants créent leurs fichiers sources et leurs projets STM32CubeIDE.
