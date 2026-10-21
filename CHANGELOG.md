# Nouveautés de Clémentine

## En préparation — 1.0.8

Sources synchronisées le 21 octobre 2026. Cette version n’est pas encore publiée en téléchargement : l’installateur et le flux de mise à jour restent sur la version 1.0.7.

- Interface disponible en français et en anglais, avec choix de langue dans Réglages et en bas à droite de l’onboarding. Le français reste la langue par défaut.
- Onboarding : roue des outils animée sans interaction ; demandes d’autorisation fiabilisées, apps Apple absentes ignorées et boutons débloqués après refus ou expiration.
- PDF : « Merge PDF » devient « Merge ». Split propose un dropdown PDF/JPEG/PNG ; pour PDF, choix « 1 par 1 » ou regroupement personnalisé des pages par glisser-déposer.
- Archives : action Dézip. Le bouton Dézip d’un ZIP épinglé le remplace dans l’Atelier par ses fichiers et dossiers après extraction réussie, en conservant le ZIP original sur le disque.
- Atelier : boutons Renommer et Supprimer sur les éléments épinglés ; confirmation avant déplacement dans la Corbeille. Retirer continue de désépingler uniquement.
- Réglages : le bouton de vérification devient « Rechercher une mise à jour ».

- Split : libellés PDF/Image, insertion de PDF avant/entre/après les groupes, rotation/duplication/suppression de pages et retrait du groupe vidé. Split est proposé uniquement pour les PDF de plusieurs pages.
- Atelier : renommage dans la ligne du document ; suivi des renommages et de la Corbeille, suppression des doublons par identité du fichier et fermeture des outils quand tous leurs fichiers ont disparu. Les autres fichiers restent sélectionnés, y compris après une modification pendant le chargement.
- Atelier : Dézip épingle les fichiers réellement extraits sur disque, icône alignée sur la roue, ordre des commandes ajusté et affichage « 0 ko ». Confirmation native de suppression conservée avec texte raccourci.
- Onboarding : langue sans icône ni libellé à droite de Retour ; changement d’outil toutes les 1,8 seconde.

## 1.0.7 — 20 octobre 2026

- Atelier : l’aperçu des dossiers utilise une icône de dossier.
- Fonctionnalités : nouvelle catégorie « Dossier » après ZIP, sans sélecteur de format, avec ZIP et les actions adaptées.
- Les dossiers ne proposent ni conversion de document ni Métadonnées, y compris lorsqu’un nom de dossier se termine par une extension de fichier.

Correctifs différentiels disponibles depuis les versions 1.0.4, 1.0.5 et 1.0.6.

## 1.0.6 — 20 octobre 2026

- Métadonnées n’est plus proposé pour les dossiers, dans la roue et l’Atelier. ZIP reste disponible.
- Les dossiers affichent « Dossier » dans la liste et l’aperçu de l’Atelier, au lieu de « Autre ».

Correctifs différentiels disponibles depuis les versions 1.0.3, 1.0.4 et 1.0.5.

## 1.0.5 — 20 octobre 2026

- Corrige la régression d’affichage : les éléments du glisser-déposer restent au-dessus de la roue.
- Recherche automatiquement les mises à jour au lancement, puis toutes les heures en arrière-plan. L’installation reste à votre initiative.

Correctifs différentiels disponibles depuis les versions 1.0.2, 1.0.3 et 1.0.4.

## 1.0.4 — 20 octobre 2026

- Finovox : sélection de l’onglet et du sélecteur Chrome fiabilisée. Le chargement se ferme après remise des fichiers au SaaS, qui gère les doublons et l’analyse.
- Glissements multiples : la roue reste au-dessus de la pile de fichiers du Finder.
- Retour haptique : suppression des impulsions répétées lors du survol avec plusieurs fichiers.
- ZIP : les lots peuvent inclure des archives, tout en masquant l’action ZIP pour une archive seule.
- Onboarding : les animations de découverte ne réagissent plus au passage de la souris.

Correctifs différentiels disponibles depuis les versions 1.0.1, 1.0.2 et 1.0.3. L’installateur complet reste disponible en secours et pour une première installation.

## 1.0.3 — 20 octobre 2026

Disponible depuis **Réglages → Chercher une mise à jour** dans Clémentine, ou via l’installateur pour une première installation.

- Mises à jour différentielles : téléchargement des fichiers modifiés lorsque le correctif est disponible, avec installateur complet en secours.
- Installation : récupération de la relance si l’ancienne instance reste ouverte et vérification de la version réellement démarrée.
- Installateur : fenêtre dédiée au glisser-déposer vers Applications ; l’ouverture depuis le disque d’installation rejoint la copie installée.
- Outils : les petites fenêtres se déplacent depuis leur en-tête, sans déplacer les illustrations de la page Fonctionnalités.
- Atelier : liste de documents limitée à la hauteur de l’aperçu, bouton Vider aligné à droite, suppression du chemin et de son bouton de copie.
- Atelier : infobulles au-dessus des boutons Preview, Finder (chemin complet), Ouvrir et Retirer.
- Métadonnées : disponible uniquement avec un seul fichier sélectionné.
- Terminal : ouverture de chaque dossier distinct de la sélection, sans doublons et avec prise en charge des espaces, accents et caractères spéciaux.

Correctif depuis la 1.0.2 : environ 311 Ko. Correctif depuis la 1.0.1 : environ 341 Ko. Si le correctif ne peut pas être appliqué, le téléchargement complet est utilisé.
