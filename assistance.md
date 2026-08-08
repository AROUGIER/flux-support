# Assistance — Flux

Flux est un lecteur pour l'abonnement IPTV que vous avez déjà. Il ne fournit
aucun contenu.

## Démarrer

Il faut une playlist de votre fournisseur, sous l'une des deux formes :

- **Xtream Codes** — adresse du serveur, nom d'utilisateur, mot de passe ;
- **lien M3U** — l'adresse d'un fichier `.m3u` ou `.m3u8`.

Les identifiants sont enregistrés dans le trousseau de l'appareil et ne le
quittent jamais.

## Les problèmes les plus fréquents

### « Le serveur a refusé ces identifiants »

Deux causes donnent le même message chez la plupart des fournisseurs :
l'abonnement a expiré, ou **une autre connexion est déjà en cours**. Beaucoup de
panneaux n'en accordent qu'une seule, et mettent quelques secondes à la libérer
après avoir quitté une chaîne. Attendez cinq secondes et réessayez ; si le refus
persiste, vérifiez votre abonnement auprès de votre fournisseur.

### Une chaîne ne démarre pas, les autres oui

C'est le flux qui est mort, pas l'application. Sur un direct, l'écran d'échec
propose **les autres exemplaires de la même chaîne** présents dans votre
playlist, en mettant en tête ceux qui ont déjà fonctionné.

### La lecture s'arrête au bout de quelques secondes

Vérifiez la mémoire tampon dans Réglages → Lecture. La valeur **Automatique** est
celle qui charge le plus d'avance ; une valeur en secondes la *limite*.

### Les sous-titres n'apparaissent pas

Flux affiche les sous-titres **texte** (SRT, ASS, mov_text, WebVTT). Les
sous-titres **gravés en images** (PGS, VobSub, DVB) ne peuvent pas être affichés
par le lecteur du système ; l'application le signale quand elle en rencontre.

### Un film annoncé « 4K » ne l'est pas

Ouvrez le panneau **Sources** pendant la lecture : Flux mesure la définition
réelle, le codec et le débit du flux, et propose de basculer sur une autre copie
sans repartir du début.

### Le bouton « Passer l'intro » n'apparaît pas

Les génériques sont repérés en comparant le son de **deux épisodes** de la même
série, sur votre appareil. Il faut donc en avoir regardé deux avant que la
fonction existe pour cette série.

## Signaler un problème

Depuis l'écran d'échec de lecture, **« Copier le rapport »** produit un compte
rendu technique complet — appareil, réseau, réponse du serveur, décisions du
lecteur. Les identifiants de votre playlist y sont **masqués à l'écriture** : il
n'existe aucun chemin qui les laisse passer. Collez-le dans votre message.

## Ce que Flux ne fait pas

- Il ne fournit ni ne vend aucun contenu, aucun abonnement, aucune playlist.
- Il ne peut pas réparer un flux mort chez votre fournisseur.
- Il ne transmet pas la vidéo à un récepteur AirPlay ; la recopie d'écran, elle,
  fonctionne.

## Contact

**[Ouvrir un ticket](https://github.com/AROUGIER/flux-support/issues/new)** —
c'est le canal principal, et le plus utile : un ticket garde la trace du
problème, permet d'y répondre publiquement, et évite que la même question soit
posée dix fois sans réponse visible. Un compte GitHub gratuit suffit.

Joignez-y le rapport produit par « Copier le rapport » : il contient tout ce
qu'il faut pour comprendre, et rien qui vous identifie.
