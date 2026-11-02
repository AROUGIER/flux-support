# Politique de confidentialité de Flux

*Dernière mise à jour : 2 novembre 2026*

## En une phrase

Flux ne collecte rien, n'envoie rien, et n'a aucun serveur.

## Ce que Flux ne fait pas

Il n'y a **aucun compte Flux**, donc aucune inscription, aucune adresse
électronique, aucun mot de passe chez nous. Il n'y a **aucun serveur Flux** : nous
n'exploitons aucune infrastructure susceptible de recevoir vos données. Aucune
analyse d'usage, aucun traceur publicitaire, aucun outil de mesure d'audience
n'est intégré à l'application.

## Ce que Flux enregistre, et où

Tout reste sur votre appareil.

| Donnée | Où elle vit |
|---|---|
| Identifiants de votre abonnement IPTV | **Trousseau** de l'appareil et, s'il est activé, votre trousseau iCloud, chiffré de bout en bout : c'est ce qui évite de retaper un mot de passe sur l'Apple TV. Jamais dans un fichier, jamais dans une sauvegarde en clair |
| Catalogue téléchargé depuis votre panneau | Dans l'espace privé de l'application |
| Historique de lecture, favoris, réglages, liste de vos playlists sans leur mot de passe | Dans l'espace privé de l'application, et dans **votre** iCloud privé si vous activez la synchronisation. Nous n'y avons aucun accès : c'est le conteneur privé de votre compte Apple |
| Contenus téléchargés hors ligne | Dans l'espace privé de l'application |

Le **mode incognito** suspend l'enregistrement de la progression et de
l'historique.

## Les services tiers que Flux contacte

Flux ne parle qu'à ces interlocuteurs, et jamais de votre part.

**Votre fournisseur IPTV.** C'est vous qui en avez choisi un et qui nous en
donnez l'adresse. Flux lui demande votre catalogue et vos flux, exactement comme
le ferait n'importe quel lecteur. Nous n'intervenons pas dans cette relation.

**TMDB** (themoviedb.org), pour les affiches, les synopsis et les distributions.
Flux envoie un **titre de film ou de série, ou une recherche d'un à trois mots
pour trouver une personne** — jamais votre identité, jamais vos identifiants,
jamais l'adresse de votre fournisseur. Ce produit utilise l'API de
TMDB sans être approuvé ou certifié par TMDB. Les offres légales affichées pour un
titre absent de votre playlist viennent de TMDB, qui les tient de JustWatch.

**iptv-org**, pour les logos de chaînes. Un seul fichier d'index est téléchargé,
au plus une fois par mois. Aucune donnée n'est envoyée.

**OpenSubtitles**, seulement quand vous cherchez des sous-titres. Flux envoie le
titre ou son numéro TMDB, la saison, l'épisode et les langues voulues.

**YouTube**, pour les vignettes des bandes-annonces. Flux demande l'image d'une
bande-annonce par son identifiant, sans rien dire de vous.

## Votre réseau local

Pendant un **AirPlay**, votre appareil sert le film au récepteur que vous avez
choisi, sur votre réseau local et derrière un jeton tiré au hasard. Le film y
circule en clair, sans vos identifiants. **Envoyer une playlist ou une lecture** à
un autre de vos appareils passe aussi par ce réseau, après un code affiché sur les
deux écrans. Rien de tout cela ne sort sur Internet.

## L'intelligence artificielle

La recherche en langage naturel s'exécute **sur votre appareil**. Flux y lit vos
phrases lui-même ; pour celles qui racontent une histoire ou une envie, il peut
s'aider des modèles de traduction et de langue que le système fournit, sur
l'appareil eux aussi. Il n'y a aucune clé d'API et aucun service tiers d'IA, et
une phrase ne quitte pas votre appareil. Seule une recherche d'un à trois mots,
qui peut être le nom de quelqu'un, part à TMDB pour en trouver le portrait.

## Contenus

Flux ne fournit, n'héberge et ne distribue **aucun contenu**. C'est une interface
pour l'abonnement dont vous disposez déjà. Nous n'avons aucune visibilité sur ce
que votre fournisseur propose ni sur ce que vous regardez.

## Enfants

Flux n'est pas destiné aux enfants et ne collecte sciemment aucune donnée les
concernant — puisqu'il n'en collecte aucune. Un contrôle parental protégé par
code permet de masquer des catégories et des contenus.

## Vos droits

Vos données n'étant qu'entre vos mains, vous en disposez directement :
supprimer l'application efface tout ce qui est local ; les réglages permettent
d'effacer l'historique, les favoris et les téléchargements séparément ; désactiver
la synchronisation iCloud retire la copie distante.

Nous ne pouvons pas vous transmettre vos données, ni les corriger, ni les
effacer à votre place : nous ne les avons pas.

## Modifications

Toute évolution de ce texte sera datée en tête de page.

## Contact

Pour toute question sur cette politique :
**[ouvrez un ticket](https://github.com/AROUGIER/flux-support/issues/new)** sur
le dépôt d'assistance. Aucune adresse électronique n'est demandée pour écrire, et
aucune n'est collectée — ce qui est cohérent avec ce que dit cette page.
