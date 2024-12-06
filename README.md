Béopy-L est une disposition de clavier ergonomique alternative au traditionnel azerty/qwerty
Elle corrige de très nombreux défauts de qwerty/azerty que vous connaissez sûrement déjà si vous lisez cette page github.
En bref Béopy-L c'est ça : 
<img width="891" alt="image" src="https://github.com/user-attachments/assets/267df7ed-27d9-4721-a8be-ac590ffc13db">
(pour essayer la disposition https://ergol.org/stats/#/beopy-l//en+fr)

Cette disposition est un mélange entre la disposition Bépo (bepo.fr) et Ergo‑L (ergol.org)
Comment est elle née ? C'est ce que je vais raconter ici :

AVERTISSEMENT: le texte ici présent et bourré de fautes d'orthographe, et je m'en tape. (regardez https://www.youtube.com/watch?v=5YO7Vg1ByA8)

J'ai d'abord découvert le bépo et j'ai commencé à écrire avec cette disposition, cependant après quelque jours à peine, je découvre le Béopy, disposition extrêmement proche du bépo faite par Berijeux https://www.youtube.com/watch?v=oX9ytatFCNA

En gros le Béopy c'est comme le bépo mais en inversant :
`O` et `P`
`E` et `I`
`G` et `Q`
`È` et `Y`
ainsi qu'une tournante : `K` -> `Z` -> `W` -> `K`

Malgré le peu de modification le béopy est une amélioration substantielle du bépo car le `W` et le `Y` sont mieux placé pour l'anglais
Exemple pour le mot « you » :
<img width="658" alt="image" src="https://github.com/user-attachments/assets/f67f05be-ce02-4478-a24e-1f6952f1db75">

Cependant le béopy à encore un gros défaut, c'est le fait qu'il ya trop de touche en extension sur l'auriculaire droit : `M`, `K`, `Z` et `Ç`

Après + de 3 ans en béopy je découvre la disposition Ergo‑L, qui corrige définitivement le problème des touches en extension grâce à un principe simple : 
« Une touche morte pour les diriger toutes »
En effet en ergo il y a une touche morte (représenté par l'étoile rouge à droite du clavier sur l'image) qui permet ensuite d'accéder à tout les accents utiles en français (indiqué en vert)
<img width="896" alt="image" src="https://github.com/user-attachments/assets/e1478841-7b4c-412a-ab8d-025894b9cd28">

J'essais donc de passer à ergo‑L pour profiter de ses avantages mais deux choses me retienne :
- la position du `J` en ergo‑L est rédibitoire, je n'aime pas dutout cette position, j'écris sur un clavier décaller et cette touche est infiniment loin de mon petit index droit. À chaque fois que je veux écrire une réponse très rapide, comme « je sais pas » je subis le mauvais placement de la touche `J`.
- J'ai le béopy dans les doigts, j'écris vite est bien, si je peux éviter de devoir tout réaprendre depuis le début je serais ravis

Alors que faire ?

Créer une nouvelle disposition, le Béopy‑L, qui implémente le principe de la touche morte d'ergo‑L pour ne plu avoir d'extension sur l'auriculaire droit, tout en ne boulversant pas l'entièreté des placements de touches auquel je suis maintenant bien habitué.

De plus l'équipe ergo‑L à fait un formidable travail pour facilité au maximum l'appropriation d'ergo‑L et mettant à disposition des outils qui permette à chacun de s'approprier ergo‑L, (encore merci kazé pour kalamine et encore merci nuclear squid pour ergo‑L et le site internet)

Je suis donc parti de Béopy, j'ai ajouté la touche morte et dégager toutes les touches en extension. J'ai également retravaillé un peu les symboles et la couche alt-gr d'ergo‑L pour rendre l'écriture en latex tout simplemment jouissive (placement de `\`, `^` ect…).

C'est ansi que je suis arrivé à Béopy‑L, le boss final, qui profite :
-De tout les avantage classique des dispositions ergonomique par rapport à qwerty/azerty
-Des chiffres en accès direct
-D'un accès à toutes les touche sans extension sur les auriculaire
-D'un placement agréable pour le `J`
-D'une couche en alt-gr avec tout les symboles de programmation et latex à porté de main

Est-ce que vous devriez écrire en béopy‑L ?
Réponse courte : Non.
Si vous venez d'azerty, passez à ergo‑L. C'est utilisé par quelque dizaines voir centaines de personne, c'est désormais dans les dispositions de base sur linux. Et vous profiterez des racourcis clavier sur la main gauche avec `C` `V` `A` `X` `S` qui sont bien placés contrairement à Béopy‑L

Vous écrivez en Bépo, vous avez envie de profiter de la plupart des amélioration d'ergo‑L sans réinventer la roue, est-ce que vous devriez écrire en Béopy‑L ?
Oui. Je pense que c'est précisement la niche dans laquelle Béopy-L peut être utile. Il existe déjà une disposition hybride entre Bépo et Ergo‑L nommé « Bépolar », je prétend que Béopy‑L c'est Bépolar mais en mieux : ça nécessite à peine plus de d'effort que de passer de Bépo à Bépolar pour une amélioration substentielle.

Béopy‑L peut aussi être considéré, si, comme moi, vous ne pouvez pas vous résoudre à la position du `J` en ergo-L/Erglace.
