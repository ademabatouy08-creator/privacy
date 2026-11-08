
# privacyPont Root ⇄ Discord

# Politique de confidentialité

Dernière mise à jour : 8 novembre 2026

Ce bot relie un salon Discord à une application dans Root. Il lit les messages des salons où il est ajouté pour les afficher dans Root, et il envoie sur Discord ce qui est écrit depuis Root. Il n'y a ni publicité, ni revente de données.

## Données que le bot traite

- Le texte des messages publiés dans les salons que le bot peut voir, et les liens vers leurs images ou fichiers joints.
- Le pseudo et la photo de profil (adresse de l'image) de la personne qui écrit.
- Les noms et identifiants des serveurs et des salons, et l'heure des messages.
- Les messages écrits depuis Root, avec le nom de la personne qui les envoie.

Le bot ne lit pas les messages privés et ne demande ni mot de passe, ni e-mail, ni numéro de téléphone.

## À quoi elles servent

Uniquement à faire fonctionner le pont : afficher les salons et l'historique dans Root, transmettre vos messages à Discord, et proposer des réponses rapides en comptant les mots les plus utilisés.

## Ce qui est conservé

- **Les derniers messages** (environ 400) restent en mémoire le temps que le bot tourne. Ils disparaissent quand il redémarre.
- **Un compteur de mots** est gardé dans une petite base de données : chaque mot et le nombre de fois où il a été dit, sans nom d'auteur.
- **Les messages écrits depuis Root** passent par une file d'attente dans cette base avant d'arriver sur Discord. Elle contient le nom de l'auteur, le texte et la date.
- **Des identifiants de messages** déjà transmis sont gardés pour éviter les doublons.

Le bot ne garde pas d'archive des conversations Discord.

## Avec qui les données circulent

- **Discord**, où se trouvent les messages d'origine.
- **Root**, où l'application affiche les messages à ses utilisateurs.
- **Cloudflare**, dont le tunnel sert de passage chiffré entre l'application et le bot.

Rien n'est vendu ni partagé à d'autres fins. Les échanges entre l'application et le bot sont protégés par un mot de passe secret.

## Hébergement

Le bot est exploité par son créateur sur son propre ordinateur ou sur un petit serveur personnel. Les données ne sont pas envoyées à d'autres services que ceux listés plus haut.

## Vos droits

Vous pouvez demander à tout moment l'accès à vos données, leur suppression (par exemple votre nom dans la file d'attente) ou l'arrêt du traitement. Pour que le bot cesse de lire un serveur, il suffit de l'en retirer : un administrateur peut l'expulser, ou lui retirer l'accès au salon.

Si vous êtes dans l'Union européenne, vous disposez des droits prévus par le RGPD, dont celui de saisir votre autorité de protection des données (en France, la CNIL).

## Mineurs

Le bot suit les règles de Discord : il n'est pas destiné aux personnes de moins de 13 ans, ou de moins de l'âge minimum fixé dans leur pays.

## Modifications

Cette page peut évoluer si le bot change. La date en haut indique la dernière version.

## Contact

Pour toute question ou demande de suppression, écrivez au créateur via son profil GitHub : [github.com/ademabatouy08-creator](https://github.com/ademabatouy08-creator).

Ce service n'est pas affilié à Discord ni à Root.
