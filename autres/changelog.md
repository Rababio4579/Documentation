---
description: >-
  Voici la liste de tous les changements effectués datés et décris depuis la
  version 4.11.2.
---

# Mises à jour
## [**5.3.5 - 05/07/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1126051989822910495)

- Le système de Live Presence et de rôle en live ont été réactivés.
- Certaines commandes personnalisées envoyant un message sans bouton fonctionnent désormais correctement.
- Les logs de modération d'unmute lancés à partir de la commande /unmute ne seront plus envoyés deux fois.
- Quelques problèmes d'affichages ont été corrigés sur les commandes /stats wolfy, /botinfo ou /sondage résultats et /item drop.


## [**5.3.0 - 23/06/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1121576226713243674)

💡 **Amélioration du système de suggestions :**

- Nouvelle page de configuration pour les suggestions.
- Il est maintenant possible de mentionner un rôle lors d'une nouvelle suggestion sur le serveur.
- Gestion des mentions et messages privés des suggestions d'un serveur spécifique possible par le membre avec la commande /suggest.
- Notifications envoyées lors du changement de statut, avec possibilité de mentionner le membre
- La partie dédiée aux suggestions dans la commande `/config` a été améliorée.
- Suggestions acceptées ou refusées déplaçables automatiquement dans des fils dédiés.
- Possibilité de bloquer les discussions dans les fils de tri dans la configuration du bot.
- Nouveau type "Prévue", accessible via clic droit ou `/suggestmod` attente et qui n'est pas pris en compte dans le nombre de suggestions simultanées par membre.
- Ajout de la possibilité de cacher le nom du modérateur triant les suggestions.
- Amélioration de l'ergonomie de la configuration des suggestions + séparation dans une nouvelle page.
- Passage de la commande `/suggest` en ephemeral pour éviter les spams dans les salons.

🚩 **Refonte du système de signalements :**

- Possibilité de signaler un membre ou un message via le clic droit en plus des commandes.
- Possibilité d'ouvrir un fil automatique pour les modérateurs à chaque nouveau signalement.
- Les signalements traités peuvent être déplacés dans des fils dédiés selon leur type.
- Ajout d'un menu au message de signalement envoyé aux modérateurs :
- Ajout de boutons : "Pris en charge", "Marqué comme traité" et "Ouvrir un ticket" (si tickets activés).
- Possibilité de sanctionner un membre sur le message si des sanctions prédéfinies existent.
- Nouvelle page de configuration pour les signalements.

📨 **Nouvelle page d'embeds :**

- Nouvelle ergonomie d'édition et de prévisualisation des embeds & boutons.
- Suppression des onglets au profit d'une barre latérale plus adaptée.
- Système de brouillons pour une utilisation furtive sans sauvegarde.
- Simplification du système de sauvegarde.
- Amélioration de l'ergonomie d'envoi & d'édition avec importation de messages.
- Nouvelle pop-up pour l'envoi d'images (liens, drag&drop, importation)
- Envoi de messages avec des profils personnalisés (photo de profil & pseudo)
- Nouveautés d'embeds :
 - Jusqu'à 5 embeds par message.
 - Personnalisation de l'icône d'avatar & de footer.
 - Possibilité d'intégrer des liens dans le titre et l'auteur de l'embed.
 - Intégration du sélecteur d'émojis.
 - Ajout des émojis aux boutons de liens.
 - Augmentation du nombre d'embeds pour les premiums (10 → 50).

🎂 **Amélioration des anniversaires :**
Ajout d'un nouveau mode "Privé/Public" pour les anniversaires.
- Public : Utilisation de la date du profil.
- Privé : Dates modifiables par les gérants du serveur avec une nouvelle commande `/adminbirthday`.

🔐 **Paramètres de confidentialité pour la modération :**
- Possibilité de cacher le nom du modérateur dans les MP de sanctions.
- Possibilité de rendre les commandes de modération éphémères.

🚜 **Nouvelle commande /topitems :**
Nouvelle commande `/topitems` qui permet d'afficher les statistiques des items sur le serveur.

🗒️ **Autres améliorations :**

- Support des nouveaux pseudos Discord (@username)
- Auto-complétion des noms d'items en circulation dans les différentes fonctionnalités de DraftBot les incluants.
- Le système des shards a été entièrement retravaillé afin d'apporter une meilleure stabilité au projet.
- Vous pouvez maintenant voir sur quel cluster se trouve votre serveur (icône + nom).
- Amélioration de la page d'accueil du `/config` Modération avec une synthèse de l'ensemble des systèmes.
- Il est possible désormais de ne plus obtenir un message d'erreur lorsqu'on supprime des messages de plus de 14 jours.
- Affichage du nombre de sanctions dans le `/sanctions list`.
- Améliorations de l'ergonomie du panel sur mobile & possibilité d'installation du site via bulle sur iPhone & iPad.
- Amélioration de l'ensemble des jeux (Puissance4, Morpion, Chifumi, Pendu, Colormind).
- Correction d'un bug important au niveau des chaînes YouTube.
- Prise en charge des posts de forum dans les salons ignorés (xp, money, logs).
- Ajout de la possibilité de créer automatiquement les salons lors de la configuration de plusieurs systèmes (tickets, suggestions, captcha, etc...).
- Ajout d'un mode de répétition "ciblé" pour envoyer les messages récurrents quotidiennement à une heure précise.

## [**5.2.4 - 19/05/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1109137561634472006)

✨ **Améliorations :**

- Amélioration de l'ergonomie et optimisation de l'espace du panel sur mobile.
- Bulle de tutoriel encourageant à utiliser la version installée du panel de DraftBot sur iPhone & iPad.
- Les liens de pages annexes de chaines YouTube sont maintenant acceptés du moment qu'elle cible un contenu de la chaine.

🐛 **Corrections :**

- La détection de victoires au puissance 4 de DraftBot est rétablie.
- Les concours (giveaways) sont maintenant de nouveau opérationnels.
- Certains éléments du panel se sauvegardent à présent correctement.
- Le message de demande de partie du Chifumi mentionne à présent de nouveau l'utilisateur ciblé.
- Les notifications sociales Reddit affichent à présent des images intégrées en haute qualité pour les posts contenant des liens.

## [**5.2.3 - 15/05/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1107552401864540170)

✨ **Nouveautés mineures :**

- Refonte complète de la commande de statistiques Brawlstars.
- Dissociation de l'option de messages collants & message réenvoyés afin de pouvoir réenvoyer les messages collants.
- Amélioration de l'ergonomie de la commande `/description`.
- Ajout des dernières règles markdown Discord à la commande `/saveconv`.
- Ajour de la possibilité de créer des posts de forums avec la commande `/envoyer`.

🗒️ **Autres changements :**

- Correction d'un bug empêchant la récupération de certaines chaines YouTube.
- Correction de certains points faibles du puissance4 et amélioration du système de priorisation des coups.
- Activation de sécurités supplémentaires pour les données envoyées depuis le panel.
- Correction de nombreux bugs.

## [**5.2.2 - 18/04/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1097940732880355358)

- Ajout du badge premium dans le profil (`/info utilisateur`).
- Correction du problème de mentions dans le social notif Steam.
- Correction du problème d'upload avec les fichiers entre 2mo et 10mo.

## [**5.2.1 - 17/04/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1097325195410292797)

- Nouvelle social-notif de jeux gratuits dans la boutique Steam.
- Intégration de la nouvelle icône premium.
- Ajout d'une modal sur le bouton d'ouverture des tickets quand l'option de demande de raison est activée.
- Ajout du nom du rôle réaction lors de la configuration sur le panel.
- Option de tri des serveurs de la barre latérale sur le panel.
- Amélioration du design du sélecteur de couleurs sur le panel.
- Contournement du bug d'émoji de Discord dans la commande `/colormind`.
- Correction d'un problème d'affichage dans la commande `/report`.
- Correction de plusieurs bugs mineurs.

## [**5.2.0 - 29/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1090743875573923850)

✨ **Nouveautés 5.2.0**

- Migration des giveaways aux boutons
- Niveau minimum d'annonces de passages de niveaux
- Nouveau module de social notif GOG pour des jeux gratuits
- Nouveau jeu de génération de grilles de démineur avec 3 difficultés
- Importation de l'économie du bot UnbelievaBoat sur DraftBot
- Nouveau type de log pour voir les utilisations de la commande /envoyer
- Nouveau mode de message collant pour le système de messages récurrents qui supprime le dernier message collant envoyé
- Nouveau mode silencieux (pour les messages informatifs) de l'auto-modération
- Nouvelle prévisualisation en image des logs générée avec les infos de l'utilisateur (Pdp, pseudo, icône serveur, icône personnalisée du log, nom du module, date/heure)
- Ajout de la possibilité de modifier un rappel (/rappel modifier)
- Les admins ne sont à présent plus concernés par la limite de suggestions en attente
- Retour des paramètres aléatoires pour la commande /love

🌐 **Améliorations panel :**

- Configuration des réactions de mots sur le panel
- Nouvelle catégorie de gestion des rôles automatiques
- Suppression automatique des flags "NEW" sur le panel lors de la visite de la page concernée par les nouveautés
- Ajout de la possibilité de détecter les rôles déjà utilisés entre les sélecteurs de rôles réactions sur le panel
- Amélioration globale du design du panel

🥳 **Nouveau sélecteur d'émojis :**

- Design entièrement basé sur celui proposé par Discord
- Optimisation des émojis pour de meilleurs performances sur téléphone et petites connexions
- Prise en charge de tous les émojis futurs ajoutés par Discord
- Amélioration du cache des émojis
- Design adapté aux téléphones
- Système de recherche poussé

## [**5.1.6 - 01/03/2023**](https://discord.com/channels/422112414964908042/599942732559024138/1080587168721932309)

- Les logs sont à présent groupés (jusqu'à 5 logs par message).
- Amélioration de tous les cooldown des commandes afin de moins limiter les utilisations rapides et plus les utilisations abusives.
- Ajout d'une prévisualisation des saveconv dans le rendu sur Discord afin d'éviter de devoir l'ouvrir dans le navigateur.
- Ajout d'une case de couleur à chaque difficulté du colormind.
- Ajout de variables d'écosystèmes aux commandes personnalisées (niveaux, économie et anniversaires) :
  - `{level}` : Niveau de l'utilisateur
  - `{level-rank}` : Place de l'utilisateur dans le classement
  - `{money}` : Argent de l'utilisateur
  - `{money-rank}` : Place de l'utilisateur dans le classement
  - `{birthday}` : Anniversaire de l'utilisateur
- Amélioration légère de l'ergonomie de l'Embed Creator sur mobile.

## [**5.1.0 - 02/02/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1070817034528624791)

✨ **Nouveautés**

- Nouveau jeu ColorMind (`/colormind`) (3 difficultés).
- Ajout des rôles réactions temporaires sur les boutons.
- Nouveau log de boosts annonçant les nouveaux et anciens boosters du serveur.
- Nouveau log lors de l'achat dans la boutique de l'économie (catégorie de log économie).
- Ajout des statistiques de jeu Valorant.
- Ajout d'indices optionnels dans la commande `/bingo` + suppression de la valeur min.
- Ajout de la possibilité de désactiver le vote neutre des suggestions.
- Ajout d'un bouton de désactivation des messages récurrents afin de faire une pause.
- Ajout de la possibilité de mettre en pause un message récurrent.
- Ajout de nouvelles commandes d'inventaire :
- `/item` donner Donner gratuitement un item
  - `/item vendre` Vendre un item
  - `/item échanger` Échanger un item contre un autre
  - `/item drop` Drop un item de son inventaire
  - `/dropitem` Drop d'item à la communauté

📈 **Améliorations**

- Retour du filtre des membres partis dans les classements de niveaux, d'anniversaires et d'économie !
- Ajout de boutons dans le `/config` pour visualiser et éditer un message récurrent.
- Commandes contextuelles Info & Profil sont maintenant visibles que par l'utilisateur qui les demandes.
- Possibilité de faire `/adminxp set` et `/adminargent set` avec un membre n'étant plus sur le serveur.

🌐 **Panel**

- Ajout d'une sécurité si on essaie de fermer le panel avec des changements non sauvegardés.
- Ajout de la possibilité de réordonner les boutons de liens dans l'Embed Creator.
- Ajout de la configuration de base des tickets (sans le message d'ouverture).
- Ajout d'un bouton "Dupliquer" aux Rôles Réactions du panel.
- Amélioration de la page équipe pour les déficients visuels.

## [**5.0.4 - 28/11/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1046598860933447680)

✨ **Changements majeurs :**

- Retour du système temporaire annuel de calendrier de l'avent 🎄
- Enregistrement automatique des mute/unmute effectués directement sur Discord dans l'historique des sanctions (auteur de la sanction inclus pour les serveurs premium ✨).
- Correction du bug d'actualisation des compteurs de membres après la première actualisation.
- Amélioration de la partie ban dans la commande `/mod`.

## [**5.0.0 - 12/11/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1040780539436744815)

Son lot d'améliorations et nouveautés va ravir nos plus fidèles habitués, et faciliter les interactions de nos nouveaux utilisateurs ! Les Commandes Slash qui remplaceront à présent nos commandes à préfixe, nous ouvrent le champs des possibilités avec @DraftBot et permettent de rendre toujours plus intuitive son utilisation. Vous disposez dorénavant de toutes les indications destinées à vous guider directement dans votre zone de message. De plus, vous pouvez facilement paramétrer les permissions pour chaque membre, rôle, ou salon, simplement depuis les paramètres de votre serveur. Pour bien commencer, vous pouvez essayer `/config` !

💥 **Commandes Slash**

- Suppression des commandes à préfixe au profit des commandes Slash.
- Maintiens des commandes personnalisées avec prefix personnalisable.

🔧 **Nouvelles actions de @DraftBot**

- Clic-droit sur un membre du serveur proposera maintenant dans "Application" un bouton qui permet d'afficher les informations ou le profil de cette personne.
- Clic-droit sur un message de @DraftBot proposera maintenant dans "Application" un bouton qui permettra d'Accepter ou Refuser dans le cas des suggestions et tickets. Des détails pourront être demandés par modal. Les messages ne permettant pas cette fonctionnalité afficheront un message d'erreur.
- Clic-droit sur un message de @DraftBot proposera maintenant dans "Application" un bouton qui permettra de récupérer le contenu d'un message, d'un embed et même le lien des images & fichiers.

🎙️ **Gain d'expérience et d'argent en vocal :**

- Fonctionnalité réservée aux @Premium ✨
- Gain toutes les 2min de vocal
- Salons AFK automatiquement ignorés
- Gain désactivé s'il y a moins de 2 personnes (bots non compris)
- Possibilité d'ignorer et booster des salons vocaux

💬 **Refonte du système de suggestions :**

- `suggest` permet d'accéder au nouveau menu des suggestions
- Affichage du statut de la liste des suggestions, leur statut et popularité
- Boutons permettant d'envoyer une nouvelle suggestion, avec un modal pour sa rédaction
- Possibilité d'ajouter une image après avoir validé sa suggestion
- Possibilité d'ajouter un commentaire à une suggestion si celle-ci nécessite des précisions
- Configuration sur Discord ou Panel Web par les administrateurs complétée : retrait des réactions après décision finale, limitation du nombre de suggestions en attente par membre, option de commentaire
- Couleur des suggestions dynamiques, changement de couleur de la suggestion en fonction des votes. Le @Premium permet de personnaliser ces couleurs ✨
- Visualisation des suggestions d'un membre précis avec /suggestmod view

🆙 **Améliorations diverses :**

- Ajout de la commande `/event`
- Ajout des auteurs des sanctions lorsque l'action est effectuée directement avec Discord pour les serveurs @Premium ✨
- Amélioration de l'ergonomie de la commande `/giveaway create`
- Ajout d'un bouton de revanche aux jeux de puissance 4, morpion, chifoumi
- Ajout des boosters de salons pour les systèmes de niveaux et d'économie
- Le compteur de membres s'actualise directement avant d'attendre les 10 minutes
- Ajout des catégories et fils aux blocages d'xp/money ainsi qu'aux boosters afin de cibler les salons enfants d'une catégorie

## [**4.16.5 - 12/11/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1014662590389035079)

✨ **Utilisation des salons vocaux textuels :**

Depuis peu, il restait une zone d'ombre dans laquelle @DraftBot ne pouvait pas faire son job, le chat écrit des salons vocaux.
Dès à présent, retrouvez y :

- Toutes les commandes Slash
- Toutes les commandes à préfixe
- L'auto-modération
- Le gain d'expérience (niveaux)
- Le gain d'argent (économie)

 **Corrections :**

- L'auto-complétion de la commande `/aide` a été corrigé ainsi que l'affichage de la description d'une commande Slash affichée via la commande `/aide <commande>`.
- L'affichage de la commande `/sanctions` list a été corrigé sur mobile.
- L'affichage du résultat de la commande visible uniquement pour l'auteur de la commande a été retirée des commandes `/adminmoney` et `/adminxp`.
- L'auto-complétion de la commande `/admininventory remove` a été corrigé.
- L'annulation de la commande `/puissance4` n'affichera plus de message d'erreur si la personne ne répond pas à la demande de jeu.
- Un problème au niveau de l'exécution des commandes `/config Niveaux` & `/config Économie` a été corrigé si trop de salons et rôles ignorés ainsi que de rôles boosters ont été configurés sur le serveur.

## [**4.16.5 - 28/08/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1014662590389035079)

![✨](https://discord.com/assets/e820a306c732b90515989dada9995a97.svg) **Utilisation des salons vocaux textuels :** Depuis peu, il restait une zone d'ombre dans laquelle @DraftBot ne pouvait pas faire son job, le chat écrit des salons vocaux. Dès à présent, retrouvez y :

> \- Toutes les commandes Slash - Toutes les commandes à préfixe - L'auto-modération - Le gain d'expérience (niveaux) - Le gain d'argent (économie)

**Corrections :**

> \- L'auto-complétion de la commande `/aide` a été corrigé ainsi que l'affichage de la description d'une commande Slash affichée via la commande `/aide <commande>`.

- L'affichage de la commande `/sanctions list` a été corrigé sur mobile.
- L'affichage du résultat de la commande visible uniquement pour l'auteur de la commande a été retirée des commandes `/adminmoney` et `/adminxp`.
- L'auto-complétion de la commande `/admininventory remove` a été corrigé.
- L'annulation de la commande `/puissance4` n'affichera plus de message d'erreur si la personne ne répond pas à la demande de jeu.
- Un problème au niveau de l'exécution des commandes `/config Niveaux` & `/config Économie` a été corrigé si trop de salons et rôles ignorés ainsi que de rôles boosters ont été configurés sur le serveur.

\

## [**4.16.4 - 28/08/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1013561250745159842)

✨ **Commandes Slash sur tous les serveurs :**

> Dès aujourd'hui, nous donnons accès **à l'ensemble des serveurs** l'accès aux <mark style="color:yellow;">commandes Slash</mark> afin de vous permettre de mieux appréhender la transition entre les commandes avec préfixe et les commandes Slash. Elles sont activées par défaut sur vos serveurs, aucune manipulation de votre part n'est nécessaire. Pour rappel, l'arrêt des commandes avec préfixe aura lieu dans la prochaine mise à jour <mark style="color:red;">**4.17.0**</mark>.

🗒️ **Modifications :**

- Les commandes personnalisées cachées de la commande `help` seront maintenant sous spoiler dans la page principale dédiée aux commandes personnalisées dans la commande `/config`.
- Changement du nom de plusieurs commandes Slash, le mot clé `update` redevient `admin` (`/updatexp`, `/updatemoney`, `/updateinventory`).
- L'annulation de l'achat d'un article dans le `!shop` ne retournera plus de message d'erreur.
- Plusieurs boutons "Annuler" inutiles ont été retirés dans la commande `/config`.

## [**4.16.3 - 28/08/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1013208694831448195)

✨ **Nouvelle fonctionnalité :**

> Ajout d'un sélecteur de jours à la fonctionnalité des messages récurrents (commandes prefix/slash & panel).

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

🐛 **Corrections :**

- Ajout de plusieurs cooldown sur quelques commandes manquantes pour éviter les abus.
- Amélioration de la stabilité globale des connections à la base de donnée.
- Correction d'un bug d'édition/suppression messages récurrents panel.
- Correction bug qui empêchait l'achat dans le shop après l'utilisation de la pagination.

## [**4.16.2 - 24/08/2022**](https://discord.com/channels/422112414964908042/599942732559024138/1012114791826993212)

📸 **Trombinoscope officiel de l'équipe**

Parce que tous ceux qui travaillent sur le projet ont une identité **:** [**https://www.draftbot.fr/equipe**](https://www.draftbot.fr/equipe)

✨ **Fonctionnalités premium**

Afin de connaitre ce qu'apporte le premium de **DraftBot**, retrouvez en bas de page un tableau comparatif **:** [**https://www.draftbot.fr/premium**](https://www.draftbot.fr/premium)

ℹ️  **Passage prochain aux commandes Slash**

Lors de la prochaine mise à jour <mark style="color:blue;">**4.17.0**</mark> nous passerons les commandes Slash en public pour tout le monde. Ce changement annoncera la fin du support des commandes à préfixe. Seules les commandes personnalisées fonctionneront encore avec préfixe.

🗒️ **Autres** changements

- Ajout de la possibilité d'ajouter des **boutons de liens** à vos embeds dans toutes les fonctionnalités (inclu d'Embed creator).
- Ajout de la commande Slash `/config` permettant de configurer l'entièreté des fonctionnalités de @DraftBot.
- Traduction des commandes Slash en français lorsque Discord est en français (les noms de commandes anglais fonctionnent toujours !)
- Ajout de l'auto-complétion des rôles et salons sur toutes les configurations d'embeds du panel.
- Ajout du moyen de paiement en plusieurs fois avec Klarna.
- Suppression du paiement par prélèvement SEPA (en raison de nombreux abus & fraudes engendrant de nombreux frais supplémentaires).

## [**4.16.1 - 17/06/2022**](https://discord.com/channels/422112414964908042/599942732559024138/987159735482585098)

🐛 **Corrections**

- Les logs de messages modifiés de plus de 1000 caractères sont a présent correctement affichés.
- Les problèmes de fonctionnement des salons vocaux privés ont été corrigés.
- La commande `!sell` affiche à présent correctement les items avec des émojis personnalisés.
- Le problème qui coupait la commande `backup` pendant la restauration du serveur a été corrigé.
- La commande `/color` affiche a nouveau les couleurs correctement.
- Le bug qui empêchait la commande `!rolereact add` de fonctionner a été corrigé.
- Les messages récurrents avec un emplacement d'image vide ne sont plus enregistrables sur le panel.
- Le défilement dans les popups pour la création/configurations des systèmes sur le panel ne sera plus bloqué sur les petits écrans.
- Les points de chargements sont à présent correctement centrés sur téléphone

## [**4.16.0 - 16/06/2022**](https://discord.com/channels/422112414964908042/599942732559024138/986759655164350504)

✨ **Nouveautés**

- Ajout des commandes Slash des catégories **Jeux** ainsi que **Modération**.
- Les rôles du membre lors de son départ seront désormais affichés dans les logs de départ.
- Ajout de markdown dans les logs de messages afin de mieux voir les modifications.
- La commande Slash `/rules update` a été ajoutée afin de modifier une règle du règlement déjà présent.
- Un argument optionnel "`raison`" a été ajouté aux commandes `/updatemoney`/`!adminmoney` et `/updatexp`/`!adminxp` pour pouvoir indiquer la raison de la modification d'argent/expérience d'un membre.
- Le temps restant avant de pouvoir de nouveau utiliser la commande `daily` est désormais visible dans le message.
- Amélioration des interactions de la commande `give`.
- Le timestamp Discord a été ajouté dans la sauvegarde des tickets, dans le `!saveconv` ainsi que sur le panel.
- Ajout d'un message dans l'attente de la finalisation des commandes de copie et de déplacement de messages.
- Les commandes `!puissance4`, `!bingo` et `!pendu` ne peuvent plus être utilisées en messages privés.
- Redirection vers la page de connexion lorsque l'utilisateur tente d'inviter DraftBot via le site web sans être connecté.
- L'affichage de la commande `premium` a été légèrement amélioré.
- Refonte du système de boutons afin qu'ils se retirent tous seuls en cas de messages d'erreurs.
- Le système de rôles réactions ne dupliquera plus les rolereacts ayant le même identifiant.
- Des bugs présents dans le sélecteur de modes des rôles réactions ont été corrigés.
- Les émojis personnalisés supprimés présent dans le serveur seront retirés des boutons et sélecteurs de rôles réactions.
- Les rôles automatiquement ajoutés par Discord (Rôle Booster, Sub Twitch, Membre YouTube, etc.) seront maintenant ignorés lors de la restauration des rôles d'une backup.
- Les URL Twitch d'utilisateurs commençant sont désormais toutes utilisables. - Plusieurs problèmes ont été corrigés lors d'actions dans les **tickets** (fermeture, suppression, réouverture...).

:**dizzy**: **Refonte du système de privateroom\*\*

- Serveurs premium pouvant aller jusqu'à 5 catégories de salons vocaux temporaires.
- Configuration des permissions attribuées à l'utilisateur.
- Ajout de plusieurs variables pour le format du nom du salon (`custom-word`, `random-word`, `index`)
- Nouvelle interface ergonomique sur le panel permettant de configurer les `privateroom`. - Affichage par défaut de la catégorie des `privateroom` défini à `@everyone`.
- Ajout d'une limite de création de 10 salons vocaux temporaires en 3 min par utilisateur.

## [**4.15.9 - 06/05/2022**](https://discord.com/channels/422112414964908042/599942732559024138/971917384124362762)

✨ **Améliorations**

- Ajout de la possibilité dans tous les systèmes de @DraftBot de cibler une catégorie au lieu d'un salon afin de sélectionner tous les salons enfants.
- Ajout de la possibilité dans tous les social-notifs d'envoyer les annonces dans les fils (même lorsque les fils sont archivés).
- Ajout de la possibilité de supprimer une récompense dont le rôle a été supprimé depuis le panel.
- L'affichage de la commande `!shards` a été améliorée afin d'afficher tous les shards de @DraftBot.

🐛 **Corrections**

- Il y avait un bug dans la matrice de l'IA de DraftBot qui le rendait nul au morpion. 🤯
- Correction d'un bug qui prévalait l'égalité en cas de victoire.
- Le rôle "Live" sera de nouveau retiré correctement lors de la fin d'un live via présence.
- Il est de nouveau possible d'ajouter une chaîne Twitch, YouTube ou un Subreddit via la commande `!socialnotif`.
- Un bug a été corrigé dans les annonces EpicGames, empêchant leur envoi sur vos serveurs.

## [**4.15.8 - 03/05/2022**](https://discord.com/channels/422112414964908042/599942732559024138/970862861054267454)

🐛 **Corrections**

- Correction d'un bug présent dans les commandes de jeux `!puissance4` & `!morpion` qui pouvait empêchait leur bon fonctionnement.
- Correction d'un bug présent lors de la création d'un message récurrent via la commande `!repeatmsg`.
- Correction de la description de certaines commandes slash.

## [**4.15.8 - 02/05/2022**](https://discord.com/channels/422112414964908042/599942732559024138/970484865092960347)

✨ **Améliorations**

- Fusion des deux commandes `/send embed` & `/send say` en `/send`
- Changement de la structure des commandes réservées aux modérateurs (suggest & ticket) : `/suggest send` => `/suggest` `/suggest ****` => `/suggestmod ****`
- Déplacement de toutes les commandes d'émotions dans la commande slash `/interact` suite à l'accès aux slash-commandes via leur sous-commande.
- Optimisation du cache de Discord.

🐛 **Corrections**

- Corrections de bugs qui empêchaient le changement de catégories dans le help.
- Correction d'un bug présent dans la suppression de tous les stickyroles d'un membre.
- Correction d'un bug présent lors de l'enregistrement des slash commandes pour les privateroom.
- Correction d'un bug présent dans le `/gameprofil` qui empêchait l'enregistrement des profils sans plateforme.
- Correction d'un bug qui empêchait l'affichage de certaines URL d'annonces Epic-Games.
- Ajout d'un avertissement si un rôle ayant la permission "admin" est en train d'être ajouté aux rôlereact.
- Correction d'un bug présent dans le système de configuration d'un sélecteur pour le message d'ouverture de tickets.

## [**4.15.7 - 29/04/2022**](https://discord.com/channels/422112414964908042/599942732559024138/969370128091336734)

✨ **Nouveautés**

- Une amélioration des onglets de l'Embed Creator sur le panel fait son apparition dans cette version. 10 onglets au total, un nouveau design (desktop + mobile) et un scroll de la barre !
- Ajout de deux nouveaux jeux à la commande `/games` et `!apps` (Land-io et Putt Party).
- Très grosse réduction du délai établi pour les annonces Epic Games de 6h à moins de 10min.
- Il est désormais possible de ne sélectionner uniquement les domaines de liens interdits (bot + panel).
- Il est maintenant possible d'éditer le nom des rôle-reactions via un simple clic (au lieu d'un double précédemment).
- Ajout de la possibilité de coller une liste de mots clés sur le panel (pour les champs de mots clés) et tout sera ajouté.
- Ajout de la possibilité de choisir parmi plusieurs résultats dans la commande de `météo` et `tv`.
- Amélioration de tous les sélecteurs sur le panel afin que le déroulant s'ouvre en haut quand il n'y a pas de place en bas.

🐛 **Corrections**

- L'affichage de la commande `daily` a été repris dans la version Slash de cette commande.
- Les images présentes dans les intégrations de liens pouvaient parfois être ré-upload lors de la censure.
- Le nombre de membres dans les commandes `serverinfo` est désormais plus lisible pour les serveurs ayant un certain nombre de membres.
- Certains problèmes d'affichages concernant des boutons qui sont toujours affichés, malgré que la commande ait été annulée, ont été corrigés.
- Des problèmes lors de la sauvegarde de plus de 100 messages dans un ticket ont été corrigés.
- Il est maintenant possible de définir l'argent de départ à 0 dans la commande `admineconomy config`.
- Correction du bug dans l'URL des jeux gratuits d'Epic-Games.
- Ajout de la somme totale d'argent dans le footer de l'embed du `daily`.
- Support de tous les émojis avec couleurs de peau, genrés et non genrés.
- Il est à présent possible d'avoir des émojis sous la forme `:emoji:` dans la boutique et dans le sélecteur.
- Changement de l'émoji utilisé lorsqu'il n'est pas possible d'afficher un émoji personnalisé pour la devise de l'économie `$` de `💰`.
- Ajout de la possibilité de lancer une commande de `/stats` sans pseudo afin de prendre l'exécuteur de la commande comme membre par défaut.
- Suppression des émojis dans le nom du serveur pour la génération du token d'interserveur.
- Correction d'un bug qui empêchait la suppression des récompenses et articles depuis le panel.

✨ **Nouvelle** slash-commands

(Premium accès anticipé) (`!slash` pour les activer)

- Utilitaires : `backup`, `qrcode`, `send message`, `send embed`, `avatar`, `color`, `maths`, `react` et `weather` .
- Fun : `birthday`, `giveaway`, `survey`, `joke`, `love`, `rolldice`, `tv` et `youtube`.
- Interaction: `interserver`, `remindme`, `report`, `restrictemoji`, `rules`, `suggest` et `ticket`.

✨ **Nouveau** module open-source pour la météo

[(DraftBot/weather-js)](https://github.com/DraftBot/weather) (typescript, promesses, parsing xml rapide, suppression des dépendances dépréciées : request, xml2js etc...)

## [**4.15.6 - 13/04/2022**](https://discord.com/channels/422112414964908042/599942732559024138/963607891615559680)

🗒️ **Corrections**

- Correction du bug critique qui désactivait certains serveurs premium (dans le cache uniquement) à 18h lors de la ronde de vérification des serveurs premiums.
- Correction d'un bug global sur le bot qui pouvait altérer certains gestionnaires de cache et donc ralentir certaines actions.
- Grosse amélioration des messages d'erreurs lis à la création de webhooks pour toutes les fonctionnalités les utilisant (logs, modération, commandes de conversations, inter-serveurs).
- Correction d'un problème présent dans plusieurs systèmes liés aux webhooks.

## [**4.15.6 - 12/04/2022**](https://discord.com/channels/422112414964908042/599942732559024138/963246541852774510)

✨ **Nouveautés**

- Nouvelle fonctionnalité de stock d'articles (premium).
- Nouvelles commandes Slash: `Économie`, `Inventaire` ainsi que `Conversations`.

🗒️ **Améliorations**

- Amélioration du `!clear <search>` qui vérifie maintenant le contenu des embeds et ne tient plus compte des minuscules & majuscules.
- Refonte complète de la commande de statistiques `!overwatch` (présentation, émojis de héros + ranked).
- Refonte complète de la commande `/updatexp` pour une meilleure expérience utilisateur.
- Ajout de la possibilité de parler pendant une partie de `!pendu` en répondant aux messages.
- Correction de l'affichage de tous les liens pour les différentes versions (prod, ptb, canary, dev)
- Correction d'un bug au niveau des cooldowns des slash-commandes.
- Correction d'un bug au niveau de la sauvegarde du placeholder des sélecteurs de Rôles-Réactions sur le panel.
- Correction d'un bug qui empêchait les commandes de déplacement et de copie de messages de traiter les messages issus de slash-commandes.

✨ **Nouvelle** slash-commands

(Premium accès anticipé) (`!slash` pour les activer)

- Economie : `money`, `topmoney`, `shop`, `daily`, `pay`, `dropmoney` et `updatemoney`.
- Inventaire : `inventory`, `give`, `updateinventory`.
- Conversations : `clear channel`, `clear conversation`, `clear messages`, `copy`, `move`, `quote` et `save conversation`.

## [**4.15.5 - 01/04/2022**](https://discord.com/channels/422112414964908042/599942732559024138/959225660742701116)

✨ **Nouveautés**

- Ajout d'une toute nouvelle page de classement de l'économie.

🗒️ **Corrections**

- Le message confirmant la création d'un ticket via un bouton est de nouveau affiché uniquement à l'utilisateur concerné.
- Un utilisateur spammant lors d'une partie de `pendu` ne retournera plus "undefined" dans la liste des lettres.
- Une meilleure expérience utilisateur (UX) est dorénavant disponible dans la commande `/gameprofil` pour la sélection de la plateforme de jeu.
- Il est de nouveau possible de supprimer une commande personnalisée via la commande `!customcommand delete`.
- Le nombre d'expérience ou d'argent maximum que peut avoir un utilisateur a été corrigé, le nombre affiché était supérieur au nombre réellement maximum.
- Un problème d'affichage dans la commande `/dropxp` a été corrigé si le nombre indiqué était supérieur à un million.
- Un problème présent dans le sélecteur de rôles du panel a été corrigé, il provoquait des problèmes dans le cas où il n'y avait pas de valeur.
- Un souci lors de l'ajout de rolereacts sous forme de réactions a été corrigé, les rôles seront de nouveaux correctement attribués.
- Les logs de suppression de messages envoyés par des bots ne seront plus envoyés afin d'éviter des logs indésirables.
- La commande `!channelinfo` est de nouveau utilisable avec tous les salons.
- Le bouton de sauvegarde sur le panel possède maintenant une animation de chargement afin d'éviter tout spam menant à plusieurs envois consécutifs de la même requête.
- La reconfiguration du système de captcha se fait à présent sans accroche, il pouvait arriver que certaines vérifications d'accès aux salons échouent.
- Ajout de sécurités afin de ne pas pouvoir dupliquer les tickets lors de leur validation.
- Les rôles récompenses étaient réattribués à l'utilisateur dès son retour, même lorsque son expérience était réinitialisée.
- Les logs ne devraient plus se désactiver sans raison et la raison de la désactivation est maintenant plus complète.
- Ajout d'une sécurité dans le cas où un ticket ne peut pas être créé et ajout d'une file d'attente afin d'éviter le spam.
- Amélioration des messages de confirmation d'activation d'anniversaire avec l'ajout de la date et de l'âge.
- Ajout de messages d'erreurs afin d'empêcher les interserveurs dans les fils.
- Les Live-Presence peuvent à nouveau fonctionner normalement, les variables de la description personnalisée se remplaçaient et empêchaient le bon fonctionnement de la fonctionnalité.

✨ **Nouvelle** slash-commands

(Premium accès anticipé) (`!slash` pour les activer)

- Niveaux : `level`, `toplevel`, `rewards`, `dropxp` et `updatexp`.
- Émotions : `cuddle`, `feed`, `hug`, `kiss`, `pat`, `poke`, `slap` et `tickle`.
- Statistiques : /stats `apex`, `brawlhalla`, `brawlstars`, `clashofclans`, `clashroyale`, `division2`, `fortnite`, `lol`, `osu`, `overwatch`, `paladins`, `r6` et `wolfy`.

## [**4.15.4 - 18/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/954169560670560286)

🗒️ **Changements**

- Amélioration de l'affichage globale des rôle-réactions de boutons & sélecteur
- Correction d'un bug présent dans la commande Clash Royale lorsque l'api de Supercell ne nous fournit pas le deck du joueur.
- Correction d'un bug présent lors de la suppression d'un rôle-réaction avec la commande.
- Correction d'un bug présent lors du lancement d'un échange d'items.
- Correction d'un bug empêchant les commandes d'informations de s'exécuter en mp.
- Correction d'un bug qui empêchait la commande `!rules` de fonctionner lorsque le règlement avait été modifié avec l'Embed Creator.
- Correction d'un bug présent dans les rôle-réactions de boutons & sélecteur lorsque le rôle était supprimé.
- Correction d'un bug interne présent lors de la validation d'ouverture d'un ticket.
- Correction d'un bug présent dans le système chargé de demander l'identifiant ou le lien d'un message dans certains systèmes.
- Correction d'un bug présent dans le système d'importation des niveaux de MEE6.
- Correction d'un bug présent dans le système d'anniversaire lorsque DraftBot n'a pas les permissions requises.
- Désactivation de la commande `!apps` dans les messages privés.

## [**4.15.3 - 17/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/953831121131565076)

🗒️ **Changements**

- Correction d'un bug qui empêchait de créer un rôle réaction à partir d'un message d'utilisateur sur le panel.
- Augmentation des limites de tailles des settings autorisés afin d'éviter à certains gros serveurs de dépasser cette limite.
- Ajout d'un message d'erreur lorsque la commande `clearchannel` est exécutée dans un fil.
- Ajout d'un message personnalisé si le membre ne peut être mute pour un problème de permissions.
- Correction d'un bug d'affichage de la date de fin dans les rappels.
- Correction d'un bug, principalement dans la commande `shop`, en cas de changement de page après un achat
- Correction d'un bug d'affichage de certains messages d'erreurs du système de tickets.
- Correction d'un bug avec la commande `quote` lors de l'utilisation de liens de messages.
- Correction d'un bug au niveau du `rolereact remove` pour la suppression de boutons.

## [**4.15.2 - 14/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/952738228883038279)

🗒️ **Changements**

- Refonte du message de confirmation de réception de la commande `!daily` (amélioration globale + ajout de la couleur personnalisée de l'économie)
- Refonte complète de la commande de statistiques Brawlhalla (Ranked 1v1 & 2v2 , émojis pour les rangs :platinum:, les légendes :artemis: et les armes :scythe:, prévision des glories :glories:, ect...).
- Ajout de 6 nouveaux brawlers à la commande de statistiques Brawlstars (:M\_:, :A\_:, :L\_:, :F\_:, :E\_:, :G\_:).
- Nombreuses corrections au niveau des modes uniques sur les rôle-reactions.
- Correction d'un bug qui empêchait de supprimer un interserveur.
- Correction d'un bug dans la commande `!sell` qui empêchait l'échange.
- Correction d'un bug dans la commande `!shop` qui empêchait l'achat d'un article.
- Correction d'un bug au niveau de la restriction des rôles des annonces de lives via présence.
- Correction d'un soucis au niveau de la saisie de date (dans la commande `!birthday` notamment).
- Correction de la taille de la fenêtre popup du site suite à l'ajout de la permission de créer des slash-commandes.
- Correction de plusieurs bugs d'affichage présents sur la page de rôle-réactions.
- Correction d'un bug au niveau de la suppression d'un émoji dans le sélecteur d'émojis sur le panel.

## [**4.15.1 - 10/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/951318493003911218)

🐛 **Corrections**

- Correction d'un bug au niveau des logs de changement de description de salon
- Correction du bug d'affichage de la page de niveaux
- Correction d'un bug au niveau de la commande warn
- Correction d'un bug qui empêchais d'exécuter des commandes personnalisées.
- Correction d'affichage des textes dans certains messages des tickets.
- Correction d'un bug au niveau de l'édition des messages depuis l'embed creator.
- Correction d'un bug présent lors de l'annulation de la commande d'interserver
- Correction d'un bug qui empêchait de valider les nombres écrits avec les points à chaque centaine (`100.000`)
- Correction d'un bug qui empêchait d'exécuter la commande profil en mp.

## [**4.15.0 - 09/03/2022**](https://discord.com/channels/422112414964908042/599942732559024138/950919931065692241)

**✨ Slash commands**

Comme imposé par Discord, les commandes Slash vont petit à petit faire leur apparition dans cette version. Elles seront dans un premier temps restreint aux serveurs premiums jusqu'à ce que leur développement soit finalisé.

Dans cette version, nous vous proposons les principales commandes des catégories de commandes **"Bot"** et **"Informations"**. D'autres commandes arriveront dans les prochaines sous-versions.

Pour les configurer, vous devrez utiliser la commande `!slash`. DraftBot vous proposera alors de les activer en cliquant sur le bouton "Activer".

**Rôle Réactions :**

Refonte complète du système de rôles réactions permettant l'ajout des boutons et sélecteurs.

**Boutons:**

- Personnaliser la couleur du bouton.
- Personnaliser l'émoji présent dans le bouton.
- Personnaliser le nom du bouton.

**Sélecteur:**

- Personnaliser le texte du sélecteur.
- Personnaliser l'émoji de l'option de chaque rôle présent dans le sélecteur.
- Personnaliser le nom de l'option de chaque rôle présent dans le sélecteur.
- Personnaliser la description de l'option de chaque rôle présent dans le sélecteur.

**Modes:**

- Ajout du mode exclusif permettant de limiter l'utilisateur à un seul rôle du sélecteur ou des boutons.

****Panel** Web :**

- Ajout de l'interface de Rôles Réactions (avec toutes les nouveautés).
- Ajout de la possibilité de choisir la couleur du système de niveaux et d'économie sur le panel.
- Ajout de la fonctionnalité vocalrole au panel.
- Ajout de la fonctionnalité localité au panel.
- Amélioration de l'ergonomie et de l'accessibilité des sélecteurs du panel (pointeur, raccourcis clavier, curseur adaptatif à la recherche, optimisation de l'espace disponible).
- Amélioration de l'animation d'ouverture et de fermeture des options sur le panel.
- Amélioration de l'affichage des notifications et de la barre de sauvegarde sur le panel.
- Correction d'un bug au niveau du chargement des utilisateurs après la place 100 des systèmes de niveaux et d'économie sur le panel.
- Désactivation des boutons de sauvegarde en cas d'erreurs et affichage de ces dernières au survol des boutons.
- Désactivation et ajout d'une animation chargement sur les boutons lorsque la requête est en cours afin d'éviter de spammer le bouton.
- Configuration de la somme d'argent de la commande !daily

****Captcha** :**

- Mention du membre dans le message du captcha.
- Ajout d'un log en cas d'exclusion du captcha.
- Ajout d'un warning dans le footer du captcha quand il y a des majuscules et des minuscules.

****Mute** :**

- Utilisation du mute de Discord pour la commande `!mute`.
- Modification de la permission par défaut de la commande !mute de `Gérer les messages` à `Exclure temporairement des membres`
- Suppression des auto-sanctions mute définitif ainsi que les mutes supérieurs à 28 jours dû à l'introduction du mute de Discord qui limite à 28 jours.

****Autres** gros changements :**

- Augmentation des limites de social notifs pour les serveurs premiums : YouTube: 5, Twitch: 5, Reddit: 10
- Ajout de la fonctionnalité de Mention des modérateurs au système de tickets (nécessite une reconfiguration).
- Ajout de la commande !daily qui permet à vos utilisateurs de recevoir un montant configuré chaque jour.
- Ajout de la possibilité de mettre des social-notifs dans des threads.
- Amélioration du système de création de règlement (système interactif).
- Amélioration du système de backup avec l'ajout de messages de confirmation pour toutes les actions de restauration ou de suppression et ajout de l'argument delete pour supprimer une sauvegarde.
- Amélioration de l'ergonomie du système de règlement + passage à un bouton pour les nouveaux règlements.
- Amélioration des règles d'acceptations des supercell ID (4 à 8 caractères)
- Augmentation de l'affichage de la boutique en mode dark de 30 à 60s.
- Optimisation des performances des systèmes d'économie & niveaux.
- Refonte de toutes les descriptions et details dans le !help .
- Correction d'un bug qui permettait de garder l'image de bienvenue et d'aurevoir après l'expiration du premium.
- Suppression du message de confirmation du !clearchannel après 10 secondes d'affichage.
- Suppression des questions qui sont annulées via cancel.

## [**4.14.11 - 16/02/2022**](https://discord.com/channels/422112414964908042/599942732559024138/943311130200272956)

🗒️ **Changements**

- Amélioration de l'affichage du coût d'un article dans le sélecteur de la boutique.
- Correction d'un problème au niveau du comptage des membres dans le système membercount quand celui-ci est sous la forme d'une catégorie.
- Ajout de la possibilité de choisir si l'on souhaite comptabiliser les bots dans le membercount quand celui-ci est sous la forme d'une catégorie.
- Renforcement de la vérification des jeux Epic-Games dans la fonctionnalité socialnotif.
- Correction d'un souci au niveau de l'actualisation des jeux dans les messages d'annonces des Lives Présence (socialnotif presence).
- Retrait du message d'alerte lorsque le délai de 60 secondes pour acheter un article dans la boutique est écoulé ; le sélecteur est désactivé.

## [**4.14.10 - 06/02/2022**](https://discord.com/channels/422112414964908042/599942732559024138/939676492986736641)

🗒️ **Changements**

- Refonte du système d'auto-modération de liens, les domaines ignorés ignoreront également tous les sous domaines.
- Ajout de la possibilité d'ajouter une note à un utilisateur ayant quitté le serveur.
- Changement des durées des offres de premium: un mois de premium correspond aujourd'hui à 30 jours et plus au nombre de jours présent dans le mois actuel.
- Correction d'un bug bloquant les liens provenant de Discord lorsqu'ils avaient un sous domaine (exemple : `support.discord.com`)
- Correction d'un bug au niveau des logs de stickers qui empêchait leur envoi.
- Correction d'un bug au niveau des messages récurrents qui laissait passer les messages avec un contenu de plus de 2000 caractères menant directement à la suppression du message récurrent.
- Correction d'un bug au niveau des embeds des social-notifs presence.
- Correction d'un bug au niveau des interserveurs lors de l'envoi d'un sticker.
- Correction d'un bug qui menait à l'arrêt de la restauration d'une sauvegarde dès son lancement (`backup`).
- Correction d'un bug au niveau de la configuration du système de captcha et du rôle Mute.
- Correction d'un bug qui menait à la désactivation du système de logs après un redémarrage sous certaines conditions.
- Correction d'un bug qui empêchait de dépasser 72h dans le système de messages récurrents. (depuis le panel uniquement)
- Correction d'un bug qui empêchait de citer un message d'un autre salon. (`quote`)

## [**4.14.9 - 31/01/2022**](https://discord.com/channels/422112414964908042/599942732559024138/937512009258373170)

🗒️ **Changements**

- Ajout de la possibilité d'accepter/refuser une suggestion depuis un autre salon que le salon réceptacle. (`suggestion accept/refuse`)
- Réduction du délai minimum d'`une heure` à `30min` avant la republication d'une annonce de live. (`socialnotif présence`)
- Correction d'un bug qui empêchait la création/mise en place du système de captcha.
- Correction d'un bug qui permettait de mettre des valeurs décimales en dessous d'une heure pour les messages récurrents.
- Correction d'un bug qui empêchait l'envoi d'un log quand un message récurrent était supprimé en raison de la suppression de son salon.

## [**4.14.8 - 25/01/2022**](https://discord.com/channels/422112414964908042/599942732559024138/935318155360866374)

🗒️ **Changements**

- Ajout du nouveau jeu de Uno (Ocho) à la commande `!apps`.
- Ajout de la possibilité de citer des messages venant de fils (`!quote`).
- Ajout d'un message lorsque le message du plateau de jeu est supprimé (`puissance4`, `morpion`, `chifumi`).
- Correction d'un problème dans le système d'annonces de jeux gratuits Epic-Games qui menait à une ratelimit à 17:00.
- Correction d'un bug au niveau du système de présence sur le panel.
- Correction d'un bug qui permettait de garder les images de bienvenue et d'au revoir même lorsque l'on avait plus le premium.
- Correction d'un bug au niveau de la modification d'un social notif subreddit sur le panel.

## [**4.14.7 (2) - 10/01/2022**](https://discord.com/channels/422112414964908042/599942732559024138/930233341070934056)

🗒️ **Changements**

- Ajout de la possibilité de modifier la couleur du système de niveau sur le panel.
- Ajout d'un message informatif lorsque aucune sauvegarde n'a été faite pour faire une restoration.
- Correction d'un bug lors de la création de récompenses et d'articles sur le panel.
- Correction d'un bug au niveau des commandes `!adminreward update` & `!adminshop update`.
- Correction d'un bug au niveau du bouton Annuler présent dans la pagination des inventaires.
- Correction d'un bug qui empêchait d'utiliser des tags Supercell anciens qui ne font que 6 caractères.
- Correction d'un bug qui réinitialisait l'icône de l'économie lorsque l'icône était un émoji non personnalisé.
- Correction d'un bug au niveau de l'affichage des personnes ayant pris le premium sur la page `/premium`.
- Amélioration du design des récompenses sur la page de niveaux.
- Amélioration des systèmes de questions afin qu'il ne prenne pas les réponses à d'autres messages.

## [**4.14.7 - 09/01/2022**](https://discord.com/channels/422112414964908042/599942732559024138/929868856237883462)

🗒️ **Changements**

- Ajout de messages détaillés au-dessus du bouton de sauvegarde lors de la création de récompenses ou d'articles sur le panel.
- Ajout de l'âge dans la commande `profil` lorsqu'il est disponible dans la commande `birthday`
- Ajout de questions supplémentaires à la commande `membercount` afin de créer les compteurs à l'endroit qui vous intéresse + Optimisation de l'ergonomie globale de la commande.
- Ajout de la possibilité de choisir si l'on souhaite que le message récurrent soit envoyé lorsque le dernier message est déjà ce même message.
- Amélioration de la détection des émojis dans tous les sélecteurs (`shop`, `sell`, `adminshop`, `admininventory`, `adminbirthday`, `adminreward`).
- Amélioration des messages d'erreur dans les systèmes de social-notifs.
- Refonte complète de l'API permettant la communication avec DraftBot.
- Mise en place d'un système permettant l'introduction d'un panel-web futur pour les rôles-réactions.
- Correction d'un bug qui empêchait de modifier son social-notif YouTube si l'on n'était pas premium.
- Correction d'un bug critique qui pouvait empêcher le chargement de votre serveur sur le panel.
- Correction d'un bug au niveau des messages récurrents qui pouvaient se supprimer dans le cas où personne n'avait parlé dans le salon depuis le redémarrage.
- Correction d'un problème au niveau du champ d'upvotes minimum requis pour le social notif Reddit.
- Correction d'un bug qui pouvait faire afficher un nombre de serveurs incorrect lors d'un double achat de premiums.
- Correction d'un bug au niveau de la fermeture de tickets avec les boutons lorsque le membre a quitté le serveur.

## [**4.14.6 - 28/12/2021**](https://discord.com/channels/422112414964908042/599942732559024138/925515616687890462)

🗒️ **Changements**

- Ajout d'informations à propos du fonctionnement de la commande `streamrole` sur le fait qu'il ne prenne pas en compte les partages d'écrans sur les serveurs.
- Ajout des logs de suppressions d'embeds et de fichiers sur un message existant.
- Correction de la prévisualisation des commandes `admincalendar` et `calendar` & disparition de ces commandes dans la commande `help` puisque la période de Noël est terminée.
- Ajout d'une sécurité si @DraftBot n'a pas la permission d'envoyer un message dans le salon permettant d'accepter ou non un ticket.
- Correction d'un bug dans la commande `adminticket message` si la raison ajoutée est déjà présente dans le sélecteur permettant d'ouvrir un ticket.
- Affichage des messages supprimés & modifiés dans les logs des messages cités.
- Correction de bugs avec les notifications sociales CommitStrip, EpicGames & Reddit.
- Correction d'un soucis dans la commande `adminsanctions` si une sanction n'avait pas de raison.
- Correction d'un bug si un bouton dépassait les 80 caractères (notamment dans la commande `admintickets message`)
- Correction d'un bug important dans le système d'auto-modération qui permettait de le contourner.
- Correction d'un bug dans les logs de threads si l'option "Tout le monde peut le désarchiver" était modifiée.

## [**4.14.5 - 18/12/2021**](https://discord.com/channels/422112414964908042/599942732559024138/921559912063066162)

✨ **Améliorations**

- Ajout du nombre de votes sur l'affichage des résultats de la commande `!survey`.
- Amélioration des explications concernant le fonctionnement de la commande `!liverole`.
- Ajout des émojis personnalisés dans les sélecteurs des systèmes `!adminbirthday`, `!admininventory`, `!adminshop`, `!sell`, `!adminreward`.
- Ajout d'une confirmation de l'exécution des commandes `clearconv`/`delconv`/`copyconv`/`moveconv`.
- Ajout de nombreux émojis à la liste autorisée dans les systèmes de DraftBot.
- Amélioration du message de confirmation de la suppression d'un message récurrent.
- Amélioration du système de détection de messages récurrents similaires qui permet d'éviter un repost du même message.
- Changement de la fréquence de mise à jour du `!membercount` suite à une limitation de Discord qui est de 10min.

## [**4.14.4 (3) - 03/12/2021**](https://discord.com/channels/422112414964908042/599942732559024138/916117302418767893)"

✨ **Améliorations**

- Amélioration des rôles temporaires dans le calendrier de l'avent, un rôle temporaire ne fera plus retirer le rôle aux personnes qui l'avaient de manière permanente.
- Optimisation de l'ergonomie de la configuration de la commande `!socialnotif presence`.
- Optimisation de l'ergonomie de la commande `!rolereact`

🐛 **Corrections**

- Bug qui empêchait la suppression d'une case de calendrier de l'avent lorsqu'il n'y avait qu'une seule case.
- Bug qui empêchait d'utiliser la commande `!quote` sur un message envoyé par un webhook.
- Bug qui pouvait parfois empêcher le gain d'argent dans les fils Discord.
- Amélioration globale des messages informant que le premium est requis pour certaines options (message moins imposant).
- Bug qui pouvait survenir lors du dépassement du délais de 60 secondes dans la configuration des `!channelsperms`.
- Bug qui empêchait l'envoi des logs de la commande (`!pay`) si la raison était une image.
- Bug qui pouvait faire apparaitre un id incorrect dans la commande `!sanctions` si le modérateur ayant fait la sanction n'était plus sur le serveur.

## [**4.14.4 (2) - 30/11/2021**](https://discord.com/channels/422112414964908042/599942732559024138/915021997778542653)

🐛 **Corrections**

- Amélioration des boutons d'activation et de désactivation dans les systèmes `!suggest` & `!report`.
- Problème lors de la création d'un message récurrent à partir d'un message d'utilisateur (`!repeatmsg`).
- Bug au niveau du message de confirmation du système de tickets.
- Bug présent au lancement de certaines commandes de manière aléatoire.
- Bug au niveau de la sauvegarde de son profil Rainbow Six Siège dans le gameprofil.
- Amélioration du message d'erreur dans la commande `!vocalrole`.

## [**4.14.4 - 26/11/2021**](https://discord.com/channels/422112414964908042/599942732559024138/913813896480063549)

✨ **Nouveautés** pour la fonctionnalité de calendrier de l'avent

- Nouveau Design
- Utilisation du sélecteur pour la suppression de plusieurs cases en même temps
- Ajout de deux nouvelles surprises possibles : Rôle temporaire & Item d'inventaire
- Accessibilité à la commande `!admincalendar` à partir du 26 novembre (une annonce bientôt

🗒️ **Changements**

- Acceptation des url de chaines Twitch partagées depuis un mobile: (`m.twitch.tv`).
- Ajout de plus de détails dans les raisons accompagnants certaines actions faites sur les serveurs Discord afin de mieux comprendre leurs origines dans les logs.
- Plusieurs corrections d'orthographe dans la commande `!admintickets`.
- Ajout des nouvelles permissions de Discord aux commandes affichant des permissions.
- Correction d'un bug dans la commande sondage bloquant parfois le processus de fin manuelle du sondage.
- Désactivation des commandes d'émotions en messages privés.
- Correction d'un bug dans le système de sélection des catégories Dealabs depuis la commande.

## [**4.14.3 (2) - 12/11/2021**](https://discord.com/channels/422112414964908042/599942732559024138/908848082781892678)

🗒️ **Changements**

- Correction d'un soucis qui n'envoyait pas les images dans l'interserver
- Correction d'un problème si un post Reddit n'a pas de description
- Correction d'un problème dans la commande `quote` ou il n'était pas possible d'utiliser la variable
- Correction d'un bug au niveau du captcha si on choisissait un salon existant lors de sa configuration
- Ajout d'un avertissement dans la commande `adminticket` message à propos d'une description trop grande pour une raison dans un sélecteur pour ouvrir un ticket.
- Certains appareils (ex: PC) n'affiche pas la description du sélecteur en totalité.
- Correction d'un bug au niveau de la restauration de backup
- Ajout lors des backup, la sauvegarde de: bannières d'invitations, de serveurs, de l'onglet découverte

## [**4.14.3 - 06/11/2021**](https://discord.com/channels/422112414964908042/599942732559024138/906331726719103047)

🎟️ **Tickets**

- Ajout de l'ouverture des tickets avec un bouton ou un sélecteur !
- Remplacement des réactions par des boutons pour la gestion des tickets.
- Ajout de la possibilité de sauvegarder jusqu'à 300 messages d'un ticket lors de sa fermeture.
- Ajout de la possibilité de personnaliser les messages d'ouverture et de confirmation de ticket.

✨ **Nouveautés**

- Ajout de la commande `emojirestrict` : permet de limiter des émojis à certains rôles uniquement.
- Ajout de la possibilité d'indiquer le lien d'un message au lieu de son identifiant.
- Ajout de la possibilité de modifier le nombre de membres max dans les salons privés.
- Ajout d'un nouveau jeu dans la commande `apps` : Checkers In The Park (jeu de Dames).
- Amélioration du design des annonces Epic Games.
- Suppression de tous les messages de confirmations du captcha au profit d'un message résumé en fin de configuration.

🐛 **Corrections**

- Problèmes de statuts dans la commande `shards` ainsi que sur la page `/statuts`.
- Panne globale présente sur le panel depuis plus d'une semaine.
- Bug permettant de participer à un `dropxp` ou `dropmoney` lorsque l'on a atteint la limite.
- Problème avec certaines preview d'images/vidéos d'annonces Reddit.
- Conflits entre les lives présence et les annonces YouTube.
- Bugs dans les commandes `adminshop` et `adminsanctions`.

## [**4.14.2 - 30/10/2021**](https://discord.com/channels/422112414964908042/599942732559024138/903780072467595275)

✨ **Améliorations**

- Ajout de la possibilité de jouer contre quelqu'un aléatoirement aux jeux `puissance4`, `morpion`, `chifumi` + amélioration globale des interfaces
- Les threads ne sont plus comptabilisés dans le système de membercount
- Les rôles gérés par des intégrations Twitch ne faussent plus le nombre de bots sur le serveur
- Ajout de la possibilité de choisir créer un message récurrent depuis un autre salon
- Transformation de l'option Annuler des sélecteur en bouton
- Suppression de la possibilité de créer un message récurrent dans un thread
- Amélioration de l'affichage des articles dans le sélecteur du shop avec les émojis lorsqu'ils sont au début du nom
- Amélioration des explications dans de nombreux messages nécessitant une réponse de l'utilisateur
- Amélioration de nombreux boutons et options de sélecteurs sur l'ensemble du bot + amélioration des systèmes de paginations
- Remplacement de tous les derniers affichages de photo de profile d'utilisateurs par ceux définis sur le serveur
- Optimisation des requêtes entre le panel et DraftBot afin de réduire la latence des petites connexions

🐛 **Corrections**

- Bug dans la génération des sauvegarde de conversations
- Bug lors de la sélection du message dans le système de sondages
- Bug dans le système de sélection de texte dans plusieurs commandes

## [**4.14.1 - 26/10/2021**](https://discord.com/channels/422112414964908042/599942732559024138/902547817640366100)

🐛 **Corrections**

- Sélection des rôles dans la commande `socialnotif twitch` & `streamrole` (possibilité désormais de sélectionner les rôles gérés et au-dessus du membre)
- Avatar dans certaines commandes pour supporter les photos de profil sur le serveur
- Retrait du sélecteur dans la commande `quote` si un seul résultat est trouvé parmi le champ de recherche
- Réintégration du `help here`
- Lien de Twitch dans la liste des chaines enregistré
- Soucis avec les commandes personnalisées qui empêchait l'envoie si le message défini n'avait pas d'embed
- Soucis dans les privateroom lors de la configuration si le serveur n'est pas premium
- Soucis dans la commande `morpion` qui empêchait le second joueur de jouer
- Soucis dans la commande `help` si le serveur a configuré une icône d'économie personnalisée et qu'elle n'existe plus
- Soucis dans la commande `socialnotif reddit` et le panel web qui ignorait la valeur du nombre minimum d'upvotes
- Bug lors la création du `vocalrole`
- Bug dans la commande `quote` lors d'une recherche avec l'identifiant d'un message

## [**4.14.0 - 26/10/2021**](https://discord.com/channels/422112414964908042/599942732559024138/902346531628273664)

✨ **Nouveautés**

- Ajout de la commande `chifumi`
- Ajout des notifications sociales : YouTube, Twitch, Lives, Reddit, Epic Games, CommitStrip & Dealabs (`socialnotif`)
- Ajout de boutons/sélecteurs pour l'ensemble des commandes de DraftBot
- Support des Threads pour l’auto-modération, commandes de conversations et plus
- Ajout de la commande `note` pour ajouter des notes à l’historique de sanctions d’un utilisateur sans le notifier
- Ajout de la commande `tv` pour obtenir des informations sur un film ou une série
- Refonte du `vocalrole`
- Ajout de la possibilité de modifier le nom des salons issus du `privateroom`
- Ajout d’une option au système de suggestion permettant d’ouvrir un thread lors d’une nouvelle suggestion
- Ajout des logs de conférence, de création, d'autocollants et de threads
- Ajout des logs d'actions sur le panel pour les nouvelles fonctionnalités (welcome, goodbye, social-notifs, suggestions)

♻️ **Améliorations**

- Refonte de la commande help avec un nouveau design et groupe "Jeux"
- Ajout des logs de threads, autocollants et conférences
- Les salons des compteurs de membres sont maintenant ignorés dans les logs
- Ajout de "Call Of Duty" au profil de jeux
- Amélioration du message lorsque @DraftBot est mentionné
- Ajout de la possibilité d'ignorer des threads pour le gain d'expérience ou d'argent
- Réinstauration des commandes dans les messages privés de DraftBot
- Amélioration de la commande `qrcode` : Ajout d'un mode lien & Wi-Fi
- Refonte des commandes `sanctions`, `premium` et `shop` avec de nouveaux designs
- Retrait de la commande `buy` suite à la refonte de la commande `shop` avec un sélecteur
- Augmentation du temps d'affichage des messages d'erreurs de permissions de 6s à 15s
- Ajout de la possibilité de ne pas supprimer le rôle « Non validé » du captcha lors de sa désactivation
- Amélioration du système de logs afin qu'il ne logue plus les suppressions de messages de commandes.
- Le tag des utilisateurs sanctionnés sera toujours affiché dans l'historique des sanctions et sera toujours affiché, même lorsque l'utilisateur n'aura plus de lien avec DraftBot
- Création ou réutilisation d'un salon pour les logs urgents
- Traduction des arguments de commandes en français
- Ajout de la possibilité de remplacer un `temprole`
- Blocage de l'achat d'un rôle dans le `shop` si le membre le possède déjà
- Utilisation de l'avatar du membre sur le serveur dans le `userinfo`
- Ajout des icônes de rôles dans le `roleinfo`
- Ajout du nombre de threads dans la commande `serverinfo`
- Ajout de boutons pour passer à l'étape d'ajout dans les commandes `socialnotif youtube/twitch/reddit`, `automod filter` et `wordreact`
- Ajout de la possibilité de reset toute la configuration de logs d'un serveur
- Ajout de messages dans le salon du ticket lorsqu'une action le concernant est réalisée

🐛 **Corrections**

- Correction d’un souci dans l’interserver pour les images de plus de 8 Mo ou de plus de 2000 caractères
- Correction d’un bug qui ne donnait pas les objets d’inventaires dans certaines situations (giveaway, cadeaux d’anniversaires)
- Correction d'un bug de duplication des logs d'`unban`
- Correction d'un bug au niveau des messages récurrents, qui envoyait un message récurrent quand le dernier message en était aussi un.
- Correction d'un bug dans la commande `birthday` au niveau de l'affichage
- Correction d'un bug qui permettait d'accéder au leaderboard d'un serveur lorsque les niveaux étaient désactivés
- Correction d'une faille de sécurité dans le système d'anti-invitations Discord où un simple `\` ou `//` avant le code permettait de brouiller le système.
- Correction d'un bug au niveau de la création des webhooks de logs
- Correction d'un bug qui peut survenir au niveau du `ban`/`tempban` lorsque le membre n'est pas sur le serveur.

🌐 **Panel**

- Ajout de la possibilité de personnaliser le message de bienvenue et d'au revoir : couleur de l'embed, couleur de fond, image de fond, recadrage de l'image
- Ajout de la possibilité de configurer les notifications sociales (social-notifs) : YouTube, Twitch, Présences, Reddit, Epic Games, Dealabs, CommitStrip.
- Support des nouveaux salons pour l'ensemble des fonctionnalités : Threads publics, threads privés, threads de news, salons de conférence.
- Ajout d'une pastille d'info afin d'informer l'utilisateur de la raison d'une limitation.
- Ajout d'un message d'avertissement en cas de réactions déjà utilisés dans le système de suggestions.
- Ajout de la fonctionnalité ouverture de thread pour les suggestions.
- Changement de l'icône pour le changement de couleur des fonctionnalités.
- Amélioration de l'interface du panel sur téléphone.
- Ajout d'un tri des serveurs dans la barre latérale en fonction du nombre de membres.
- Ajout d'une transition lors de l'affichage des boutons de connexion sur le panel

## [**4.13.18 - 14/09/2021**](https://discord.com/channels/422112414964908042/599942732559024138/887127715965177876)

✨ **Améliorations**

- Ajout de la commande `!youtube`.
- Optimisation de la vitesse de chargement de la liste des serveurs sur le panel.
- Ajout de la possibilité de supprimer l'image de fond des messages d'arrivée et de départ.
- Suppression du salon `#shards` (pour une question de performances), préférez utiliser la page status du site web.
- Ajout de sécurités supplémentaires concernant les permissions des membercount.
- Grosse amélioration du système de gestion des shards (devrait permettre de réduire les problèmes causés par la latence de Discord).

♻️ **Corrections**

- Correction d'un bug au niveau de la commande `clearchannel` qui déplaçait progressivement le salon vers le haut.

## [**4.13.17 - 02/09/2021**](https://discord.com/channels/422112414964908042/599942732559024138/882793415744581693)

♻️ **Corrections**

- Correction d'un bug au niveau des statistiques du jeu Rainbow Six Siège.
- Correction d'un bug dans le gameprofil lorsque la plateforme était rentrée en majuscules.
- Correction d'un bug d'affichage dans la boutique quand un rôle temporaire était supprimé.
- Ajout d'une sécurité à la commande `!8ball` lorsqu'un sticker ou une image est envoyé en guise de question.
- Ajout de sécurités supplémentaires lors de la création d'un ticket.
- Ajout de logs d'erreurs lors d'erreurs lorsque l'attribution des cadeaux d'anniversaire échoue.
- Ajout de sécurités dans le système de rôle en vocal.
- Correction d'un bug dans le système d'interserveurs lorsqu'une liaison est coupée.
- Correction d'un bug au niveau de la désactivation de serveurs premiums sous certaines conditions.
- Correction d'un bug au niveau du délais de 60 secondes dans la commande `!rappel`.

## [**4.13.16 - 25/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/879873667499192330)

✨ **Améliorations**

- Ajout de la question d'affichage de l'âge à chaque changement de date d'anniversaire.
- Amélioration du système de messages de bienvenue et d'au revoir pour que les messages soient tout de même envoyés lorsque l'image ne peut pas être générée.
- Optimisation du changement des images sur le panel et pour les systèmes avec fond personnalisé (`!welcome`, `!goodbye`).
- Réécriture complète du système de captcha avec permettant d'ajout d'erreurs plus précises concernant chaque cas d'erreur.
- Déplacement de la commande `!quote` vers la catégorie Conversations
- Ajout de sécurité au niveau de la validation des pseudos dans la commande `!paladins`.

♻️ **Corrections**

- Correction de l'importation de la version pour le système de release dans Sentry
- Correction d'un problème au niveau de la création du rôle mute.
- Correction d'un bug au niveau de l'affichage d'un giveaway avec comme récompense un rôle supprimé.
- Correction d'un bug au niveau du suivi des actions temporaires.
- Correction d'un bug présent sur le panel au niveau du sélecteur de couleurs de l'Embed Creator.

## [**4.13.15 - 24/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/879495954565308506)

✨ **Améliorations**

- Ajout de l'argument `delete` à la commande `!description`.
- Ajout d'une sécurité au système de giveaway lorsque l'embed est supprimé.
- Optimisation du système de captcha.
- Ajout de sécurités lors de la modification des permissions de salons lorsqu'ils sont créés pour les systèmes de captcha & mute.
- Ajout de la permission voir le salon aux permissions requises de DraftBot pour l’exécution des commandes de déplacement de conversations.
- Passage de 250 à 200 caractères pour le nom d'un article dans la boutique afin d'éviter une erreur de longueur.

♻️ **Corrections**

- Correction d'un bug qui empêchait l'affichage des statistiques Wolfy d'un utilisateur qui avait pour rôle favori l'héritier.
- Correction de la commande `!adminrole clear`.
- Correction des priorités des messages d'erreurs de la commande `!moveconv`.
- Correction d'un problème avec la commande `!paladins` qui indique que le joueur est introuvable alors qu'il existe bel et bien.

## [**4.13.14 - 16/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/876830777453727744)

✨ **Améliorations**

- Optimisation de la commande de configuration du captcha.
- Optimisation de la rapidité de la commande `!buy`.
- Amélioration du clearchannel, le salon est maintenant supprimé avant sa duplication afin d'éviter les problèmes de limites de salons.

♻️ **Corrections**

- Bug présent dans le système de channelperms une fois les 30 secondes d'attente dépassées.
- Bug présent au niveau de la mise à jour des permissions des salons pour le mute et le captcha si DraftBot n'avait pas la permission administrateur.
- Bug dans le userinfo lorsque l'utilisateur n'a aucun badge.
- Bug au niveau des statistiques qui permettait dans certaines conditions d'envoyer la plate-forme dans un mauvais format.
- Bug au niveau du système de logs de rôles lors de la création d'un rôle sans permission.
- Bug au niveau des récompenses de niveaux uniques.
- Bug au niveau des logs de ratio depuis le panel.
- Bug au niveau des logs de salons et de rôles lors de l'affichage des permissions.
- Bug dans la commande `!moveconv` lorsque les messages étaient plus vieux que de 2 semaines.

## [**4.13.13 - 15/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/876244147776913458)

✨ **Améliorations**

- Amélioration de la gestion des erreurs afin de mieux gérer les futurs problèmes et interventions.
- Amélioration de tous les messages d'erreurs, ils apportent maintenant la solution exacte pour chaque cas spécifique.
- Amélioration des fréquences d'actualisation des compteurs de membres.
- Vérification des permissions avant de supprimer les messages dans l'automod.
- Ajout de la permission "Attacher des fichiers" aux permissions requises par défaut pour l'execution de toutes les commandes.
- Ajout d'une sécurité à la commande `normalize` si la normalisation n'est pas possible.
- Ajout de sécurités aux commandes `games`, `suggest`, `react`, `membercount` et `giveaway` dans le cas où DraftBot n'aurait pas les permissions requises
- Ajout de 10 shards supplémentaires.

♻️ **Corrections**

- Une erreur de conception dans le système de récompenses
- Plusieurs bugs concernant la commande de statistiques `paladins`
- Mentions des interserveurs provoquant un affichage moins propre sur téléphone
- Problème d'affichage des logs de modifications de permissions pour les salons
- Un glitch qui permettait de rentrer des nombres à virgules sur le panel
- Un problème d'édition des messages sur l'embed creator sous certaines conditions
- Bug retirant l'image des logs sur le Panel lorsque le salon choisit était modifié

## [**4.13.12 - 13/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/875809308573589534)

✨ **Améliorations**

- Amélioration de la gestion de problèmes dans le système de giveaway.
- Amélioration de la gestion des erreurs au niveau des actions temporaires (tempmute, tempban, temprole, rappel).
- Optimisation du système de votes.

♻️ **Corrections**

- Bug présent dans le système de logs de salons lors de l'affichage des permissions.
- Bug présent dans la suppression des messages du moveconv.
- Bug présent dans la commande de statistiques du jeu Rainbow Six Siège.
- Bug présent qui provoquait des spam des mp lors d'un glitch de dépassement de limite de serveurs premium avec des serveurs supprimés.

## [**4.13.11 - 12/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/875189320527527956)

✨ **Changements**

- Refonte du système de détection des infractions (il gagne en rapidité et en réactivité)

♻️ **Corrections**

- Bug d'affichage de noms de l'infractions dans certains cas dans le système d'auto-modération.

## [**4.13.10 - 05/08/2021**](https://discord.com/channels/422112414964908042/599942732559024138/872613706696130580)

✨ **Changements**

- Optimisation du chargement de la page premium.
- Optimisation du chargement de DraftBot.fr en ne chargeant Stripe que dans la page premium.
- Amélioration de la liste des liens dans la commande `!help`
- Changement des arguments `desactivate` en `deactivate` dans les commandes `!birthday` et `!premium`.
- Nombre de brawlers dans la commande de statistiques de Brawlstars.
- Ajout des nouvelles variables manquantes au système d'anniversaire (`{date}`, `{time}`, `{timestamp}`)
- Désactivation des messages de bienvenue lorsque DraftBot n'a pas les permissions nécessaires.
- Logs d'`Arrivés & départs` renommés en `Arrivées & départs`.

♻️ **Corrections**

- Bug présent lors d’une commande personnalisée avec une image seulement.
- Bug au niveau de la backup avec les salons stage et threads.
- Bug de duplication d'images dans la commande `suggest accept/refuse`.
- Bug dans le sélectionneur de rôles qui prenait un rôle aléatoire lorsqu'un Sticker ou Fichier était donné.

## [**4.13.9 - 28/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/869715964403519578)

✨ **Nouveautés**

- Ajout des 3 nouveaux brawlers sur les statistiques: Squeak, Buzz et Griff.
- Changement de la valeur minimale du bingo (1 - 10000).
- Blocage de la création d'une commande personnalisée lorsque le nom est déjà utilisé par une commande.
- La commande delconv permet maintenant de supprimer des messages ayant été envoyés avant les 100 derniers messages.

♻️ **Corrections**

- Correction d'un bug d'affichage au niveau de la variable `{time}`.

## [**4.13.8 - 26/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/869011100082003988)

✨ **Nouveautés**

- Amélioration du système du système anti-invites afin de bloquer toutes les invitations non officielles. (`discord.io`, `dsc.gg`, `dsc.ink`, `dsc.lol`, `discord.limited`, `discord.homes`, `discord.fyi`)

♻️ **Corrections**

- Bug d'affichage de couleur dans la commande `!adminlogs` lors qu’aucune couleur n'a été définie.
- Bug du nombre d'items dans dans la commande de création d'un item pour les récompenses.
- Bug présent dans la commande `say` lorsqu'une image est envoyé sans contenu.
- Bug présent au niveau de la fonctionnalité d'évents qui empêchait son arrêt.
- Bug au niveau des rôles temporaires en conflits avec la suppression manuelle du rôle.
- Bug lors de l'affichage des noms de rôles avec les récompenses de niveau.
- Bug présent lors de la récupération de rôles uniques au retour d'un membre sur le serveur.

- Bug présent au niveau de la variable `**{time}**`.

## [**4.13.7 - 24/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/868274024986312704)

✨ **Nouveautés**

- Nouvelle commande `temprole` pour ajouter un rôle temporairement à un membre.
- Intégration des rôles temporaires à l'ensemble de l'écosystème de DraftBot :
  - Commandes personnalisées
  - Récompenses de niveaux
  - Articles d'économie
  - Récompense de giveaway
- Ajout de la possibilité à DraftBot de jouer au morpion.
- Ajout de difficultés aux jeux `puissance4` & `morpion`.
- Ajout de 3 nouvelles variables : **{date}**, **{time}** et **{timestamp}** qui permettent respectivement d'afficher la date et l'heure et le timestamp en secondes.
- Amélioration du sélecteur d'émojis (émojis personnalisés en haut de liste) et du sélecteur de rôles multiples sur le panel.
- Amélioration de le commande `userinfo` (badge pour les membres de l'équipe et suppression du tag qui était déjà dans la description).
- Optimisation de la commande `admininventory`.

♻️ **Corrections**

- Nombreuses optimisations ayant pour objectif de réduire les problèmes de déconnexion causés par la latence l'API de Discord.
- Bug au niveau de la couleur des rôles dans le champ de sélection des rôles boosters.
- Bug présent lors d'un envoi de message d'erreur pour le captcha.
- Bug présent lors de la création de messages d'anniversaires personnalisés avec le mode lock (depuis la commande).
- Bug présent lors d'un `adminreward update` d'un rôle supprimé.
- Bug présent lors du relancement d'une action temporaire.
- Bug présent dans la sélection de durée qui prenait l'unité mois par défaut au lieu de minutes.

## [**4.13.6 - 15/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/865345866026188830)

✨ **Nouveautés**

- Nouvelle commande `sell` vous permettant de vendre vos items d'inventaire aux autres membres (avec logs).
- Possibilité de désactiver la suppression du ticket s'il est fermé par un admin (`admintickets config`).
- Ajout de la commande `!diagnose commande` pour afficher le statut, les rôlesperms et les channelperms d'une commande.

♻️ **Corrections**

- Ajout d'un délais de 15 minutes par 10 utilisations de la commande `say` afin d’éviter le spam.
- Correction d'un bug avec l'envoi des webhooks lors d'un `moveconv` d'un message de bot.
- Correction d'un bug présent dans les logs de récompenses de niveau au retour d'un membre.
- Correction des vérifications de permissions pour le système de messages récurrents.
- Quelques corrections sur la page de niveaux (espacement + ordre des récompenses).
- Correction du problème avec la position du salon avec le `clearchannel` lorsque le salon se trouve dans une catégorie.
- Correction de la liste de toutes les permissions nécessaires à la commande `!help <commande>`.
- Correction d'un bug présent au niveau du changement de salon pour les logs.
- Tri des permissions lors de leur affichage sur l'ensemble des fonctionnalités.
- Ajout de l'alias "game" pour la commande de jeux Discord.

## [**4.13.5 - 14/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/864627722562830356)

♻️ **Changements**

- Correction du message de confirmation de mise à jour d'un rôle de la boutique lorsque l'ancien rôle est supprimé (`adminshop update`).
- Ajout d'un message d'erreur dans la commande `level` & `money` lorsqu'une photo de profil est invalide.
- Ajout d'un message d'erreur approprié lorsque le plateau de jeu du puissance4 ou du morpion est supprimé juste avant le tour suivant.
- Ajout d'un message d'erreur dans la commande de règlement lorsque le règlement est supprimé pendant l'ajout d'une règle.
- Ajout d'un message d'erreur (et émojis remis par défaut) dans le système de suggestions si l'un des émojis perso a été supprimé.
- Correction d'un bug présent dans la commande `adminlevel ignore` (message pour la demande du salon)
- Correction d'un bug présent dans les commandes custom lorsque le rôle voulant être ajouté/retiré est déjà possédé ou non par le membre.
- Messages d'xp ou d'argent ignorés si le membre n'est pas encore en cache afin d'éviter de futurs erreurs ou ratelimits (max 10min d'attente après un redémarrage)
- Correction d'un bug présent dans la commande `adminxp` qui permet d'avoir un niveau négatif.
- Correction d'un bug présent lors de la génération des images sur le panel lorsque l'utilisateur n'a pas de photo de profil.

## [**4.13.4 - 12/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/863922198565879819)

♻️ **Changements**

- Correction d'un bug présent lors de l'utilisation de la fonctionnalité ban dans le cas où le membre est au dessus de DraftBot.
- Correction d'un bug présent dans l'autorole lorsque tous les rôles ont été supprimés.
- Correction du problème présent lors d'un changement de salon pour les logs.
- Multiples vérifications ajoutés au système de captcha afin d'assurer son bon fonctionnement.
- Ajout des salons vocaux et stages dans le sélecteur du panel web.
- Correction d'un bug présent dans le système d'administration des tickets.

## [**4.13.3 - 12/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/863922198565879819)

****✨** Ajouts & Améliorations**

- Ajout de la commande `games` pour jouer aux applications de Discord (Fishington, Échecs, YouTube, Betrayal & Poker).
- Optimisation du temps requis pour le lancement de tous les shards: `25` => `15` minutes.
- Amélioration du sélecteur de salons sur le panel (nom de la catégorie, icones en fonction du type, salons vocaux, stages, catégories, message lorsqu'il n'y a pas résultats lors d'une recherche)
- Amélioration des logs de pseudos en ajoutant l'ancien pseudo.
- Ajout d'une rétrogression des rôles uniques lors d'une suppression d'expérience manuelle avec la commande `adminxp`.

♻️ **Corrections**

- Correction d'un bug présent dans la restauration de la fonctionnalité backup.
- Correction d'un problème de permissions présent dans la fonctionnalité d'acceptation de suggestions (`suggest accept`).
- Correction d'un problème lors de l'utilisation de l'argument français `accepte` de la fonctionnalité de suggestions.

## [**4.13.2 - 08/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/862487688057847828)

♻️ **Changements**

- Correction du système de sondages dans le résumé.
- Correction du bug présent dans le saveconv.
- Amélioration de la récupération des participants du giveaway.
- Correction d'un bug présent dans les logs de changements de permission d'un salon si aucune permission n'est ajoutée au rôle ou membre sélectionné.
- Amélioration du captcha. (plus précis & arrêt du système si le membre quitte le serveur)
- Correction de l'emoji qui ne s'affiche pas dans les commentaires des suggest accept & refuse.
- Réécriture et optimisations des systèmes supportant les réactions. (events, rôle réactions, tickets)
- Correction d'un bug présent dans les autoroles.
- Correction d'un bug de génération des images d'annonces de réception de récompenses.
- Correction des bugs dans les messages d'infractions bloquant aussi les auto-sanctions.
- Correction d'un bug présent dans les dates d'anniversaire.
- Correction de l'authentification sur le panel depuis la commande panel + redirection après avoir invité DraftBot.
- Ajout de l'accès à la page serveurs aux serveurs premium même lorsqu'ils ont moins de 100 membres.
- Correction de tous les logs provenant des actions du panel.
- Correction des logs de sanctions temporaires.

## [**4.13.1 - 06/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/861773314578055168)

♻️ **Corrections**

- Correction du bug présent lors de l'affichage de la commande `!welcome show`.
- Ajout de l'aide des commandes (`suggest accept` & `suggest refuse`) dans la page communautaire sur le panel pour l'option de modération.
- Correction du bug des logs d'invitations lorsqu'il n'y en avait pas.
- Correction du bug présent dans l'affichage des anniversaires du jour dans la commande `!birthday`.
- Correction du bug présent dans les embeds des commandes personnalisées lorsqu'il n'y avait qu'un seul embed.
- Correction d'un bug présent avec les webhooks des commandes de conversations.
- Correction d'un bug au niveau de la commande `suggest <accept/refuse>` lorsqu'il n'y avait pas de raison.
- Mise en privé de la liste des serveurs sur le userinfo (réservée aux membres de l'équipe de DraftBot).
- Correction du lock des serveurs premium sur le panel.
- Correction d'un bug présent lors de l'activation de la mention dans le système de reports.
- Correction d'un bug de mentions lors de messages d'annonces d'anniversaire.

## [**4.13.0 - 05/07/2021**](https://discord.com/channels/422112414964908042/599942732559024138/861667820970704946)

✨ **Nouveautés**

- **🎂 Nouveau système d'anniversaire :**
  - Annonces d'anniversaire :
    - Heure d'envoi personnalisée
    - Whitelist/Blacklist de rôles autorisés
    - Mention d'un rôle
    - Choix du salon
  - Rôle d'anniversaire temporaire le jour de l'anniversaire :
    - Rôle donné et retiré à minuit
      - Whitelist/Blacklist de rôles autorisés
    - Cadeaux d'anniversaires. (Rôle, Xp, Argent, Item, Custom) (2 sans premium et 5 avec le premium)
  - Annonces ciblées illimitées : (premium)
    - Membre ou rôles
    - Création du message avec l'Embed Creator
      - Blocage de la possibilité de voir le message pour la personne ciblée.
- **📂 Nouveau système de logs :**
  - Logs catégorisés
  - Logs des actions du panel
  - Logs avec des Webhooks
  - Logs pour les infractions
  - Refonte du design de tous les logs
  - Couleur de l'embed personnalisé
  - Possibilité d'ignorer des salons dans les logs
  - Salon personnalisé pour chaque type de logs
    - Avatar personnalisé pour chaque type de logs (premium)
    - Couleur personnalisée de l'embed pour chaque type de logs (premium)
- Ajout de Minecraft dans le gameprofil
- Ajout de la fonctionnalité channelperms pour interdire les commandes à certains salons
- Ajout des commandes `!react` & `!rappel`
- Ajout de la possibilité d'accepter ou de refuser une suggestion (`suggest accept`/`suggest refuse`)

🌐 **Panel** web

- Ajout du système d'onglets sur l'Embed Creator (2 ou 5, si le serveur est premium ou non)
- Ajout de la page communautaire (suggestions & signalements)
- Ajout du badge "Premium" sur le panel pour les serveurs qui le sont
- Invitation de DraftBot dans une fenêtre popup avec redirection vers le panel sans rechargement de page
- Ajout du choix de la devise depuis le panel pour les serveurs premiums
- Amélioration du sélecteur d'emojis sur le panel
- Correction d'une faille avec le CTRL+V dans les champs
- Embed Creator :
  - Correction d'un bug qui cachait les \`codes\` dans les fields de l'Embed Creator
  - Augmentation jusqu'à 4096 caractères pour la description d'un embed
- Limite de modifications de la date d'anniversaire (avec affichage du temps restant avant la prochaine modification)
- Accessibilité aux serveurs des shards, même lorsque d'autres ont crash ou sont pas encore lancés
- Optimisation du site en chargeant Stripe que sur la page premium
- Amélioration des sélecteurs de rôles, ils sont maintenant sélectionnables avec les flèches directionnelles du clavier
- Possibilité de modifier les rôles & salons interdits/autorisés des commandes par groupe
- Augmentation du nombre de caractères dans l'Embed

♻️ **Autres** changements

- Ajout des nouveautés premium à la commande et à la [page premium](https://www.draftbot.fr/premium)
- Possibilité de doubler l'xp et/ou l'argent si le message fait plus de 250 caractères
- Possibilité de réinitialiser l'xp ou l'argent d'un membre lorsqu'il quitte le serveur
- Possibilité de demander à l'utilisateur une confirmation avant l'envoi de sa suggestion
- Augmentation des commandes personnalisées de 50 à 100 pour les serveurs premiums
- Amélioration du mute :
  - Texte : ❌ Réactions & envoyer des messages
  - Vocal : ❌ Se connecter & parler
  - Conférence : ❌ Demande de parole
- Réécriture de tous les logs
- Réattribution des rôles récompenses au retour d'un membre sur le serveur
- Possibilité en tant que modérateur des tickets d'ouvrir un ticket pour un membre (`adminticket open`)
- Possibilité d'ajouter des images aux reports (de membres) et récupération des images des messages (pour les reports de messages)
- Activation automatique du slowmode lors de l'activation d'un interserveur
- Refonte et optimisation du système de giveaways
- Refonte et optimisation du système d'inventaires
- Correction de la pagination du shop, des récompenses, des commandes personnalisées
- Pré-shot de la fonctionnalité "Niveau de suretée" sur la commande `!guildinfo`
- Ajout d'un message de confirmation après la création d'un ticket
- Amélioration du système d'anti-spam d'emojis, (les variantes d'émojis ne sont plus comptés comme des émojis à part entière)
- Ajout de nombres au système de sondage afin de s'y retrouver plus simplement
- Augmentation de la limite de caractères pour la question des sondages: 100 => 250
- Ajout du temps restant avant de pouvoir refaire la commande `backup restore`
- Ajout des bots du serveur dans la commande `diagnose support`
- Lorsqu'un modérateur des tickets ferme un ticket, le salon ne sera plus obligatoirement supprimé
- Possibilité d'échapper les variables dans les messages (pour faire des exemples) (`\<user.username>`)

## [**4.12.1 - 17/04/2021**](https://discord.com/channels/422112414964908042/599942732559024138/832926338842492928)

✨ **Nouveautés**

- `dropmoney` & `dropxp` : Ces deux nouvelles commandes vous permettrons de faire gagner une certaine somme d'xp ou d'argent à la première personne cliquant sur la réaction.
- `admininfraction` & `adminsanction` : Ces deux nouvelles commandes vous permettrons de gérer les infractions et sanctions de vos membres. (réinitialisation des infractions/sanctions du serveur et le retrait/réinitialisation de sanctions/infractions d'un membre)
- `adminticket` : Ajout de la possibilité d'ajouter plusieurs rôles modérateurs à la gestion des tickets.
- `report` : Possibilité de mentionner un rôle lors d'un signalement d'un de vos membres.
- `copyconv` : Ajout d'une nouvelle commande vous permettant de copier une conversation à l'image de la commande `copymsg`
- `welcome`/`goodbye`/`customcommand`/`adminreward`/`adminlevel` : De nouvelles variables sont disponibles (membre, serveur & salon)
- `automoderation filter` : Ajout d'un mode strict (choisissez si vous souhaitez détecter uniquement les mots exacts).

**⚡️Améliorations**

- `repeatmsg`: Un message récurent ne s'enverra pas si le dernier message est le même message récurent.
- `ticket` : Suppression du message de confirmation de création d'un ticket après 10 secondes.
- `autosanctions` :
  - Ajout de la possibilité d'ajouter une durée aux autosanctions qui n'ont comme déclencheur une seule infraction.
  - Ajout dans les logs du serveur des sanctions effectuées par l'auto-sanction.
- `brawlhalla` : Ajout des dernières armes & brawlers.
- `sondage` : Ajout de l'alias `poll`
- `vocalrole` : Les salons AFK du serveur ne permettront plus le rôle "Vocal".
- `config` : Ajout d'un message de résumé à la fin de la commande.
- Global : Amélioration de la découpe des éléments lorsque plusieurs sont attendus dans un message (retours à la ligne & guillemets d'iPhone).
- Commandes utilisant un système de pages : Amélioration du système de pagination.
- Systèmes utilisant des webhooks : Les webhooks peuvent maintenant supporter des fichiers et les mentions sont tout le temps désactivées.
- Panel web :
  - Auto-Sanction : Amélioration de l'affichage pour une meilleure compréhension.
  - Economie : Ajout de la limite de l'argent de départ.

🐛 **Résolutions** de bugs

- `brawlhalla` : Si le joueur n'avait pas de clan, la commande tournait en boucle.
- `privateroom` : Correction du bug d'auto-whitelist des salons.
- `inventory` : Argent masqué si le système d'économie est désactivé.
- `automoderation filter` : Ajout d'une limite de 30 caractères par mot dans le filtre de mots.
- `event` : Correction du bug avec rôles si l'objectif n'était pas atteint.
- `adminreward` : Correction du bug des récompenses qui s'affichent mal dans les messages depuis la variable **{reward}**
- Panel web :
  - Commandes personnalisées : Correction du bug de drag\&drop dans les étapes

## [**4.12.0 - 25/03/2021**](https://discord.com/channels/422112414964908042/599942732559024138/824600432503685120)

✨ **Nouvelles** fonctionnalités

- Auto-Modération (disponible également sur le panel)
  - **Filter:** filtre de mots (configuration de mots, whitelist de rôles et de salons, possibilité de désactiver la censure)
  - **Invites:** Anti invitations discord (whitelist de rôles et de salons, possibilité de désactiver la censure)
  - **Liens:** Anti invitations discord (possibilité de whitelist des noms de domaines, whitelist de rôles et de salons, possibilité de désactiver la censure)
  - **Anti-spam:** Anti spam de messages (configuration du temps ainsi que du nombre de messages autorisés, whitelist de rôles et de salons)
  - **Mentions:** Anti spam de mentions (configuration du temps ainsi que du nombre de mentions autorisés, whitelist de rôles et de salons) (spécial car entre messages)
  - **Emojis:** Anti spam d'emojis (configuration du pourcentage d'emojis ainsi que du nombre du nombre d'emojis autorisés, whitelist de rôles et de salons)
- Auto-Sanctions (disponible également sur le panel) : Ajout de règles de sanctions suite aux infractions de l'automodération
- Sticky roles : Ces rôles seront conservés même après un retour sur le serveur, le rôle mute par exemple.

➕ **Ajouts**

- `inventory` : Ajout de la possibilité d'afficher l'inventaire d'un autre membre
- `customcommand` : Ajout de points de vérification pour que la commande ne continue pas les étapes si l'étape précédente n'a pas été réalisée.
- `adminreward` : Ajout de la possibilité de changer l'unicité d'un rôle reward depuis l'argument update
- `rolereact` : Ajout d'une erreur si on dépasse les 20 réactions autorisés par Discord.
- `ticket` : Ajout d'un message d'erreur si on dépasse les 50 tickets dans la catégorie
- `puissance4`: Ajout du curseur pour voir quel était le dernier mouvement de l'adversaire
- `joke` : Ajout de la possibilité de désactiver des types de blagues (**dark** et **limit** désactivés par défaut)
- `wordreact` : Ajout de la possibilité de mettre des débuts de phrases plus uniquement des mots
- `privateroom`: Ajout de la possibilité de rendre permanents des salons vocaux dans une catégorie de privateroom
- `logs` : Ajout de la date de création du compte Discord dans les logs d'arrivés systématiquement
- `suggest` : Ajout de la possibilité de mettre des images dans les suggestions
- `clear` : Ajout de la possibilité de supprimer les messages d'un membre (même s'il n'est plus sur le serveur)
- `gameprofil` : Ajout du jeu Plato (disponible également sur le panel web)
- Panel web :
  - Récupération de la couleur et du pseudo de DraftBot (Embed Creator & Messages récurrents)
  - Commandes personnalisées :
    - Ajout de la possibilité de changer l'ordre des étapes en drag-and-drop
  - Embed Creator :
    - Ajout des fields en une ligne
    - Récupération de la couleur et du pseudo de DraftBot pour l'embed creator ainsi que pour le repeat-message
- `infractions` : Ajout de la commande pour voir les infractions d'un membre
- Global : Ajout de la possibilité de sélectionner 332 emojis nouveaux dans les différents systèmes de DraftBot

**⚡️Améliorations**

- `roleperms` : Ajout d'une priorité pour les membres admins (accès à toutes les commandes)
- `adminreward` :
  - Suppression des récompenses reçues lorsque l'on reset toutes les récompenses afin que les nouvelles récompenses puisses être reçues à nouveau
  - Suppression automatique des récompenses d'un membre si son xp redescend en dessous du seuil de la récompense
- `maths` : Gestion de toutes les variantes de caractères mathématiques
- `autorole` : Ajout d'un avertissement si les rôles ne sont pas accessibles lors de la configuration
- `logs` : Amélioration des logs de modification et création d'un rôle
- `giveaway`, `event` & `survey` :
  - Si le salon cible n'a pas les permissions requises DraftBot vous donne un délai pour en sélectionner un autre ou changer les permissions
  - Si le rôle à ajouter n'est pas accessible ou ne pourra pas être ajouté, il laisse également un délai supplémentaire pour en sélectionner un autre ou changer la hiérarchie
- `buy` : Blocage lors de l'achat d'un rôle si la personne l'a déjà
- `botinfo` : Amélioration de l'affichage des nombres
- `privateroom` : Affichage des arguments si la personne est admin sinon on affiche le message de présentation
- `event` : Amélioration de l'affichage des dates
- `giveaway` : Proposition de l'activation des système de niveaux et d'économie s’ils sont désactivés lors de la création d'un giveaway avec ajout d'xp ou de money
- Panel web :
  - Ajout de la possibilité de réglementer l'accès aux commandes aux rôles Twitch et bots

♻️ **Autres** changements

- `clearchannel` : vérification des salons de modération et de règlement avant exécution de la fonctionnalité
- `adminmoney` : addition minimal mise à 0 (afin d'éviter les ajouts négatifs et suppressions positives)
- `adminxp` : Ajout de la vérification des récompenses lors de l'achat d'xp ou modification manuelle de l'xp
- `inventory` : Ajout de vérifications supplémentaires pour ne pas dépasser le nombre autorisé d'items dans l'inventaire
- `filter` & `admininvites` : Déplacement de ces deux commandes dans la commande **automoderation** (commande de rappel en cas d'oubli)
- `wordreact` : Le reset du système mettra plus les wordreact par default, il laissera une liste vide et désactivera le système
- `giveaway` & `event` : Suppression des giveaway & events si le message a été supprimé pour ne plus être limité
- Global :
  - Récupération de tous les membres en cache afin de proposer des données tout le temps complètes
  - Ajout de raisons détaillées à toutes les actions dans les audit logs de Discord afin de comprendre pourquoi DraftBot à fait tel ou tel action: création de rôles, de salons, de webhooks, attribution de rôle, changement sur le serveur
  - Ajout et suppression automatique des rôles premium sur le Support Discord

## [**4.11.6 - 24/12/2020**](https://discord.com/channels/422112414964908042/599942732559024138/791726801915084800)

✨ **Nouvelles** fonctionnalités

- `event` pour organiser des regroupements de participants
- Inventaire avec nouveaux items d'inventaire
  - Ajout d'une nouvelle commande `deal` pour effectuer des échanges d'objets
- `sondage` avec génération d'image, timer de fin (optionnel), statistiques
- Localité sur le `profil` (personnalisable avec `locality`)
- Commande `panel` pour être redirigé vers son profil ou le panel du serveur

**⚡️Améliorations**

- Refonte de la fonctionnalité `admininvites`:
  - Plus de message privée
  - Détection de toutes les invitations
  - Censure des invitations
- La commande `birthday` n'affichera plus que les membres présents sur le serveur
- Ajout des logs des transactions d'économie
- Ajout de la possibilité de customiser le message de confirmation du système de suggestion
- Ajout de la possibilité de désactiver un serveur premium même après l'avoir quitté
- Augmentation des limites des commandes personnalisées de 10 à 20 de plus pour les non premium et de 20 à 50 de plus pour les premium
- La désactivation du système de ticket ne supprimeras plus, ni la catégorie, ni les salons de tickets
- Ajout du nouveau rôle à la commande `wolfy`
- Adaptation du `morpion` au pavé numérique

🌐 **Panel** web

- Page profil (anniversaire, description, jeux)

♻️ **Autres** changements

- Lors de l'activation ou la désactivation des commandes, le nom d'une commande aura la priorité sur le nom d'un groupe.
- Optimisation globale du cache des serveurs, nous ne garderons en cache que les infos des serveurs qui ont DraftBot sur leur serveur.

🐛 **Résolution** de bugs

- Fix du système de lexique (les ensemble de mots sont maintenant détectables)
- La désactivation du système de ticket ne supprimeras plus, ni la catégorie, ni les salons de tickets (demande la communauté)
- Suppression de la commande translate suite à une inaccessibilité quasi permanente à l'api de traduction
- Suppression de la fonctionnalité "no xp" pour les membres en mode invisible (demande de Discord)

## [**4.11.5 - 19/10/2020**](https://discord.com/channels/422112414964908042/599942732559024138/769006813194092574)

➕ **Ajouts**

- Ajout de la possibilité d'utiliser tous les signes mathématiques ASCII `+﹢⁺₊＋-﹣⁻₋-﹡×÷⁄/`
- Ajout de la possibilité d'avoir le prefix de DraftBot en le mentionnant
- Ajout de la fonctionnalité de plage horaire des messages récurrents
- Ajout de la commandes `!votes` avec comptage des votes dans les webhooks
- Ajout des infos Appareil et Activité à la commande `userinfo`
- Ajout de la possibilité de terminer un giveaway
- Ajouts de modes pour les rolereact
- Ajout du `diagnose support`
- Ajout de la fonctionnalité d'anniversaires
- Anniversaire ajouté au profile

♻️ **Modifications**

- Changement de catégorie la commande `wordreact` vers interaction
- Séparation de la commande `userinfo` en deux commandes `userinfo` et `profil`
- Vérification des messages lors de l'édition (`admininvites` et `filter`)

🐛 **Résolutions** de bugs-bugs"

- Bug du `clearchannel` dans un salon communautaire
- Fix de la commande `filter` lorsqu'il y a trop de mots a afficher

## [**4.11.4 - 27/09/2020**](https://discord.com/channels/422112414964908042/599942732559024138/759890185008840736)

✨ **Nouvelles** fonctionnalités

- Ajout de la fonctionnalité `report`
- Ajout de la fonctionnalité de commandes personnalisées (create, reset, fonctionnement)
- Ajout du système de dés complet
- Refonte totale des `autoroles` pour en avoir plusieurs (3 non premiums) (5 max)

♻️ **Changements** DraftBot

 **✨** Ajouts

- Ajout du vanish a la commande `puissance4`
- Ajout de la fonctionnalité `diagnose view`
- Ajout de la fonctionnalité `diagnose rewards`
- Ajout du temps que le bingo a duré dans le footer de l'embed de fin
- Ajout de l'xp de l'utilisateur dans les récompenses

 **🔧** Général

- Refonte totale des autoroles pour en avoir plusieurs (3 non premiums - 5 pour les premium)
- Design et ergonomie du marché noir retravaillé
- Messages de captcha supprimés après validation ou dans le cas d'erreurs 6 secondes
- Salons de la commande `diagnose` triés
- Les premiums sont maintenant stockable jusqu'à 5 serveurs
- Amélioration de l'affichage de la commande `groupes`
- Catégorie de la commande `admintickets` changé
- Auto-suppression des messages de `captcha`
- Fonctionnalité d'import de niveaux de MEE6 dans la commande déplacé de la commande `config` vers`adminlevel`
- Blocage de l'activation du premium si il est déjà activé par quelqu'un d'autre sur le serveur en question
- Modification Premium :
  - Premium à vie passé de 5 serveurs à 1
  - Premium 1 an passé de 5 serveurs a 3
- Mise à jour de la page des fonctionnalités premium de la commande `!premium` (plus de 10 commandes perso, plus de 3 autoroles)

🌐 **Changements** Panel Web

- Sélection des commandes dans le roleperms rendu plus précis.
- Possibilité de sélectionner plusieurs rôles et plusieurs salons à ignorer en une fois dans la page dédié aux niveaux
- Ajout de la page custom commandes au panel web
- Ajout de la page messages récurrents

🐛 **Résolutions** de bugs

- Bug du serveur premium qui ne s'active pas après son activation sur le site (cache non actualisé) résolu
- Erreur ajouté quand on essaye de clearchannel un salon de la communauté
- Bug des premiums non retirés réglé
- Problème avec la taille des raisons dans la commande sanctions résolu (toutes les raisons sont maintenant limités a 1000 caractères)
- Bug du `!report config` lorsqu'un membre s'appelle config résolu
- Bug des repeats messages qui se mettent pas à jour après la sauvegarde des modifications
- Lorsque le nombre de custom commandes dépasse les 10 pour les premiums, les commandes restent créables mais sont ignorés, et mis en rouge, si le nombre est de 20 commandes le bouton se grise et la création est limité à 20 commandes
- Correction du problème de calcul des niveaux dans l'adminxp add
- Correction du problème du backup avec les salons news
- Correction du problème des messages invalides qui coupaient le processus des commandes rules et rolereact
- Mise à jour de la date des timestamps embeds des repeat messages
- Gestion des problèmes de perms lors de l'ajout de rôles dans les customs commandes

## [**4.11.3 - 02/08/2020**](https://discord.com/channels/422112414964908042/599942732559024138/740500989265707039)

➕ **Ajouts** Welcome/Goodbye

- Pouvoir activer et désactiver directement (`on` ou `off`)
- Pouvoir afficher le message actuel
- Pouvoir reset toute la fonctionnalité
- Couleur embed (premium)
- Dégradé de fond (pressets pour non premium) et custom pour les premium
- Images de fond (premium)
- Message déplacé dans la description donc possibilité d'ajouter des liens

✉️ **Changements** Tickets

- `!ticket create` devient `!ticket`
- `!ticket config` devient `!adminticket config`
- Nouvelles fonctionnalités **add** et **remove** pour ajouter un membre au ticket `!adminticket`

💎 **Changements** Premium

- Les administrateurs peuvent maintenant ajouter le premium à leur serveurs
- Le premium est automatiquement ajouté après achat et une page propose d'activer les serveurs

🎮 **Jeux**

- Ajout du jeu Morpion

♻️ **Autres** changements

- Refonte complète des messages de logs et conclusion des commandes de config
- Configuration des rôles permissions depuis la page Commandes du panel web avec l’icône ⚙️
- Ajout de la commande `!diagnose` pour connaître les problèmes de permissions avec le mute

## [**4.11.2 - 24/06/2020**](https://discord.com/channels/422112414964908042/599942732559024138/725133760386957385)

✨ **Nouvelles** fonctionnalités

- Nouvelle commande `!saveconv` permet de sauvegarder une conversation sous forme de page web
- Nouvelle commande `!qrcode` permet de générer un QRCode avec votre photo de profile au milieu
- Nouvelle commande `!description` permet d'ajouter une description à votre profil globalement ou sur un serveur précis

**⚡️Améliorations**

- Attribution des récompenses de niveaux améliorée, elles sont maintenant données dans l'ordre avec leur niveau correspondant
- Amélioration du design des messages de questions avec choix d'emojis
- Emojis customisés pour les commandes captcha, privateroom, ticket, interserveur, description

🌐 **Panel** Web

- Refonte des previsualisations de messages de bienvenue, d’au revoir, de niveaux et des récompenses avec un support complet du markdown de discord
- Ajout des emojis custom du serveur au sélecteur d'emojis des champs de texte
- Ajout des rôles boosters au panel web pour les niveaux et l'économie
- Ajout de la fonctionnalité Niveau maximum au panel (réservé aux premiums)
- Amélioration globale des pages de configuration pour les appareils mobiles

## [**4.11.1 - 15/06/2020**](https://discord.com/channels/422112414964908042/599942732559024138/722199124253999106)

🏘️ **Général**
 - Lancement de parties de Puissance 4 contre DraftBot ou un autre bot bloqué
 - Notification de l'utilisateur en mp lorsqu'il reçoit un premium
 - Ajout d'un respect de hiérarchie pour le système de rôles perms

**Panel Web**
 - Retour de la page https://www.draftbot.fr/levels/
 - Retour des photos de profils dans la page des donateurs
 - Refonte complète de l'UX du Panel pour une meilleure expérience sur ordi, tablette et mobile
 - Optimisation sur la rapidité de changement du panel

🐛 **Résolution de bugs**
 - Bug d'affichage du topmoney réglé
 - Bug d'affichage du message `adminmoney remove` réglé
 - Bug d'affichage des récompenses réglé avec une pagination sur 3 pages maximum si l'on dépasse 1024 caractères
 - Bug d'affichage des commandes `adminreward remove` et `adminshop remove` réglé avec une troncature suivie de `...` si l'on dépasse 1024 caractères
 - Bug de reset des récompenses réglé
 - Bug du bouton qui s'étain lors d'un reload pour visibilité d'un serveur infos sur le panel réglé
 - Bug d'importation des niveaux de MEE6 dans DraftBot réglé
 - Bug d'affichage pour la commande `!sanctions` réglé

 - Améliorations de la commande puissance4
   - 30s de délais en plus durant un tour
   - Si le joueur n'a pas joué durant 30s après le délai supplémentaire, l'adversaire est déclaré comme gagnant par forfait
   - Nomination du joueur concerné dans les messages (cas où plusieurs parties seraient en cours dans le même salon)
   - Ajout d'un message lorsque le joueur cible refuse la partie
 - Ajout d'un message informatif lorsque la commande `!ticket` ne contient pas d'arguments
 - Ajout du nom de la commande dans les messages d'erreur pour un gain de temps lors des reports

**Panel Web**
 - Ajout d'une nouvelle page dans sur le panel web **Gestion des commandes**
 - Optimisation des pages accueil, commandes, serveurs et niveaux
 - Optimisation de l'embed creator
 - Retour des images dans l'embed creator pour l'envoi et l'édition


## [**4.11.0 - 13/06/2020**](https://discord.com/channels/422112414964908042/599942732559024138/722199124253999106)

 **Vue général :**
 - Les commandes sont harmonisées et annulables en répondant `cancel`
 - Plus d'informations sont fournies dans les commandes de type `...info`
 - Nouvelles fonctionnalités : `interserver` & `suggest`
 - Nouvelles commandes : `normalize` & `sanction`
 - Commandes améliorées : `rolereact` ; `traduction` ; `cite` & `sondage`
 - Commandes supprimées : `strawpoll` & `roletorole`
 - Les messages de DraftBot qui restaient en fin de commande sont à nouveau supprimé
 - L'édition des commandes après envoi est supprimée
 - Le bot ne modèrera plus vos message s'il s'agit d'une commande

**Fonctionnalités Modération :**
 - La suppression d'un **message épinglé** avec la commande `clear` nécessite une confirmation
 - Les commandes de modération sont simplifiées et exécutables en une seule ligne
 - Nouvelle commande `unban`
 - La commande `sanctions` est maintenant accessible grâce à la **permission** *Gérer les messages*
 - Les sanctions de l'utilisateur ne sont plus affichées dans le `userinfo`

**Fonctionnalités Interaction :**
 - Le rôle de gestion des tickets pourra maintenant automatiquement **Gérer le salon** du ticket
 - Les tickets fermés peuvent être **réouverts** avec la réaction 🔓
 - Vous pouvez **supprimer définitivement** un ticket en cliquant sur 🗑️
 - Deux couleurs permettent de connaître l'état du ticket :
Avec la **couleur de DraftBot** les demandes de ticket ou ceux fermés par le membre
Les tickets acceptés ou supprimés par un Admin seront quant à eux en **rouge**
 - Le lexique peut-être modifié plus facilement en **ajoutant plusieurs mots**
 - Les messages contenant un mot interdit sont maintenant **corrigés** et renvoyés par DraftBot !

**Fonctionnalité Niveaux :**
 - Vous pouvez **réinitialiser** la configuration des niveaux avec avec `adminlevel reset`
 `adminxp resetall` permet maintenant d'**effacer les niveaux et l'XP** du serveur.
 - Même si le système d'économie est désactivé, l'argent des **récompenses est reçu**.
 - Les récompenses de rôles supprimées ne sont plus masquées
 - Enfin, deux fonctionnalités premium sont ajoutées:
   - Un **niveau maximum** empêchant ainsi le gain d'XP supplémentaire
   - Modifier la **couleur** de la fonctionnalité

**Fonctionnalité Economie :**
 - Utilisez maintenant `admineconomy reset` pour **réinitialiser** la configuration de l'économie.
Pour **effacer** la totalité de l'argent du serveur utilisez  `adminmoney resetall`.
 - Dans la boutique, les rôles supprimés mais en vente ne sont plus masqués.
Le prix de l'article est rappelé lorsqu'un article de la **boutique du serveur** est acheté.
 - L'achat d'XP est maintenant possible dans la boutique, même si le système de niveaux est désactivé.
 - Pour les serveur premiums, vous pouvez dorénavant :
 - Changer l'**icône de votre monnaie**
 - Modifier la **couleur** de la fonctionnalité

**Fonctionnalité Statistiques :**
 - Les messages du **GameProfil** ont été uniformisés
 - Vous pouvez maintenant **mentionner** un membre à la suite d'une commande pour voir ses statistiques
 - Les commandes **Paladins** & **ApexLegends** ont été retravaillées
 - Les commandes **LOL** & **R6** ont été améliorées et complétées par de nouvelles statistiques.
 - La commande **Wolfy** a été retravaillée pour améliorer le design et supporter les nouvelles photos de profil
 - La commande **BrawlHalla** a été mise à jour avec les traductions en Français et la possibilité de lier son profil ID Steam
 - La commande **CS:GO** est définitivement **retirée**

**Commande Giveaway :**
 La précision du **temps restant** a été améliorée.
 Vous pouvez maintenant **relancer** un giveaway pour obtenir un nouveau gagnant.
 De nombreuses possibilités de **configuration** complètent la commande :
*Nom de giveaway, nouvelles récompenses, choix du salon lors de la commande, nombre de gagnants...*

**Panel Web :**
- La sélection d'un rôle ou salon est simplifiée grâce à un **champ de recherche**.
- Les **salons d'annonce** sont maintenant reconnus sur le Panel Web.
- Optimisation du **chargement** du Panel Web, notamment sur mobile.
- En cas de problème sur le Panel, une notification vous expliquera quelle erreur s'est produite ainsi que ses raisons.
- Si votre **communauté** a plus de 80 membres, vous pourrez ajouter votre serveur à notre page "Serveurs"

**Embed Creator :**
**Correctifs** de bugs divers
- Le champ **"Auteur"** a été ajouté, il est affiché dans la partie inférieure d'un message embed.
- **Markdown** de Discord reproduit à l'identique : commentaires, style de police, spoil, liens, emojis ...
 - L'ajout d'**images** est plus rapide et n'entraîne plus de lags.
 - Les serveurs premium peuvent **sauvegarder** des embeds qu'ils souhaitent réutiliser ultérieurement.

## [**4.10.2 - 03/02/2020**](https://discord.com/channels/422112414964908042/599942732559024138/676817384274919453)

**🌐 Site Web:**
 - La page de niveaux est actuellement disponible sur mobile, avec une interface plus adapaté aux différents tailles d'écran.
 - Vos pages de niveaux ont leur propre nom, ce qui signifie qu'elles pourront être retrouvées sur votre moteur de recherche si elles sont souvent visitées !

**🚨  Logs:**
 - Ajout des logs vocaux
 - Ajout des logs de privaterooms
 - Ajout des logs de tickets
 - Ajout des logs de salons
 - Ajout des logs de bans/kicks effectués depuis discord
 - Mise à jour des logs de sanctions

**💰  Levels & Economie:**
 - Une nouvelle fonctionnalité voit le jour du coté des Niveaux et de l'Economie.
 - C'est l'ajout de rôles boostés: Cette fonctionnalité permet de booster en experience et en money certains rôles afin qu'ils fassent gagner plus d'experience et d'argent à ceux possédant des rôles particuliers.
ℹ️ Cette fonctionnalité est disponible depuis la commande `adminlevel` & `admineconomie`

## [**4.10 - 03/02/2020**](https://discord.com/channels/422112414964908042/599942732559024138/674010543031320586)

**🌐 Site Web:**
 - Voici le tout nouveau site https://www.draftbot.fr/ après les screens, les spoils et les sondages, il est enfin disponible sur vos navigateurs !
 - Un nouveau design à l'image de DraftBot, retrouvez les pages dédiées aux commandes, aux serveurs et niveaux qui ont été mises à jours, mais également une page maintenant dédiée aux Premium merci à eux ❤️. 
 - Ne manquez pas prochainement la découverte de nouvelles pages et ajouts tels que le PanelWeb qui est toujours en développement et apportera une plus grande simplicité ainsi qu’une vue d'ensemble que n'offrent pas les messages sur discord.

**🚨  Modération:**
 - Système de filtrage de vocabulaire réactivé
 - Ajout de la fonctionnalité annulation (`cancel`) aux commandes de sanction
 - Ajout des deux commandes de sanctions temporaires `tempmute` et `tempban`
 - La commande mute ne supprime plus les messages du joueur sanctionné mais à présent retire la permission de parler dans le salon, la notification en message privé a également été supprimée.
 - Le message lorsqu'un membre quitte le serveur est modifié par le message de sanction s'il s'agit d'un kick ou d'un ban.
 - Remplacement de la commande `warnlist` par `history`, qui répertorie maintenant toutes les sanctions d'un utilisateur.

## [**4.9.7 - 28/12/2019**](https://discord.com/channels/422112414964908042/599942732559024138/660477942484303883)

🎟️ **Nouvelle fonctionnalité !**
Cette nouvelle fonctionnalité a été demandé depuis bien longtemps, elle a donc vu le jour dans cette nouvelle mise à jour !
Cette fonctionnalité est dès maintenant disponible ! C'est le système de tickets !
Reprenant les fondamentaux d'un système de tickets sur discord, il a été revisité façon DraftBot avec une utilisation des réactions !

🦄 **Complet et simple**
Depuis le début nous cherchons à réaliser l'outil le plus complet possible, mais aussi le plus simple d'utilisation.
C'est pour cela que dans cette mise à jour, nous avons encore simplifié les **noms**, les **descriptions**, les **aliases**, les **exemples** et même les informations du help ||`!help <commande>`|| ! 

🚀 **Quelques optimisations**
Certaines fonctionnalités ont été optimisés tel que les niveaux et l'économie, les giveaways, les messages récurrents et la génération d'images !
Les requêtes faites à discord ont elles aussi été réduites, le bot est donc plus réactif 🏓 

🪂 **Quelques améliorations**
De nombreuses autres améliorations on vu le jour, qui ont également été très demandés:
 - Le reset de levels et d'économie pour tout un serveur
 - L'ajout des permissions par defaut aux privateroom
 - Des commandes executables en un seul message

🐛 **Résolution de bugs**
Comme vous avez pu nous rappeler qu'il y avait encore de petits bugs cachés, nous les avons traqués et exterminés ! 
Si vous en recontrez de nouveaux n'hésitez pas à nous les signaler dans le salon <#616670089550364702> !

## [**4.9.1 - 07/12/2019**](https://discord.com/channels/422112414964908042/599942732559024138/652777556730445834)

🎠 **Toujours plus vite !**
Grâce au passage vers la base de données PostgreSQL vous pourrez noter que DraftBot est plus rapide !
Sa mise en place a permis notamment de préparer le terrain pour les sanctions temporaires qui verront bientôt le jour 😉 

🎩 **Messages revisités et améliorés**
Les messages ont dans leur majorité été retravaillés et améliorés, les performances de notre nouvelle base de donnée nous permet d'afficher plus d'informations !

✨ **Toujours plus de fonctionnalités !**
Encore une fois, de nouvelles fonctionnalités ont vu le jour, et d'autres ont été améliorés et ça grace à toutes vos <#599942741140701194> un grand merci à vous ❤️ 

🐛 **Résolution de bugs**
Comme vous avez pu nous rappeler qu'il y avait encore de petits bugs cachés, nous les avons traqués et exterminés ! 
Si vous en recontrez de nouveaux n'hésitez pas à nous les signaler dans le salon <#616670089550364702> !

Bonne journée !


## [**4.9.0 - 02/11/2019**](https://discord.com/channels/422112414964908042/599942732559024138/640275784153432084)

🎩 **Messages plus claires, plus élégants**
Les messages envoyés par DraftBot lors des commandes ont été retravaillés afin d'être plus compréhensibles, mais nous retrouvons également un nouveau look pour les messages d'erreur et un nouveau type de message voit le jour: « information ».

✨ **Toujours plus de fonctionnalités !**
Les commandes tel que __RoleRéaction__, __RôleToRôle__, __Captcha__, __Filter__ et toutes les commandes de __Sanctions__ ont été améliorés d'un point de vu fonctionnalités et ergonomie.

📰 **Des logs restent des logs**
Les logs sont maintenant plus courts, plus explicites et ne sont plus une simple copie des messages envoyés après une commande. 
Ils sont à présent tous configurables !

🎮 **Gamer un jour, Gamer toujours...**
Le jeu __Division 2__ voit le jour dans la catégorie Statistiques mais également dans le GameProfil !