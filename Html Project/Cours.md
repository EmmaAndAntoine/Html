# Espace de Cours 1.0

Bienvenue dans ton espace de cours ! C'est un espace que je t'ai créer pour que tu apprennes sans que je sois la ! Bien évidemment, on 
pourra en discuter plus tard ! Soit indulgente, je vais essayer d'être le plus clair possible ! Tous les jours, je mettrai la page
a jour avec de nouvelles choses ! Bon codage !

// Attention ce cours n'est fait que pour le Html !

# 0.1 Légendes du cours 

Quand tu vois ca : "" ->  Il n'y a pas de chevron pour éviter certaines
erreurs mais elle doivent obligatoirement lors de l'écriture d'un scrypt avoir des chevron.


# 1.0 : Le Html

Le html est l'acronyme de HyperText Markup Language est un langage informatique qui permet de concevoir un site internet a partir d'un
script en .htm ! Il est crée en 1993 et avec le HyperText Transfer Protocol (http) et l'adresse e-mail la base du World Wide Web !
Ce langage permet de structurer ses composants grâce a des tableaux et surtout des méthodes beaucoup moins difficiles a utiliser !

# 1.0.1 Les balises

Les balises quelquels soit s'ouvre avec un chevron droit "<", plus le defini de la balise (html) et elle se referme avec un chevron
gauche. Seulement les balises sont délimité : elle commence a un endoit et se termine à un autre : On appelle cette balise, "balise
de fermeture.
. Exemple pour définir un titre : "<title></title>" -> On peut voir que la balise de fermeture se compose d'un chevron droit, d'un 
slash, le defini de la balise et un chevon gauche.

# 1.0.2 Balises spéciales

Certaines balises, comme des définitions, ne se ferment pas : elles sont dîtes spéciales !

# 1.1 : Les Constituants

Quelque soit le site, quelque soit le project, un scrypt Html se compose toujours de :

. "<Doctype Html!>" -> Cette balise indique que le scrypt sera en Html ! 

. "Head" -> Cette balise permet de déclarer la tête du scrypt ! 

. "<Title>" -> Ce balise permet de définir le titre de la page !

. "Body" -> Cette balise permet de déclarer le corps du scrypt donc les composants visibles sur le site !
 
 Ces constituants sont obligatoire pour le bon fonctionnement du scrypt ! Il ne faut bien sur pas oublier de nommer le scrypt avec
 l'extansion .htm qui permet de faire reconnaitre au navigateur qu'il s'agit d'un scrypt html !
 
 # 1.2 Faire reconnaître au navigateur la typographie de la langue
 
 Pour éviter des problêmes de typopagrapie au niveau de la langue et surtout le monde des charactère unicode, les developpeurs ont créer
 une table qui se nomme la table ASCII ! C'est une table qui permet de convertir un charactère en 0 ou en 1. Ensuite, le compilateur se 
 charge de convertir les charactère ! Et bien en Html, c quasiment la même chose mais en différent. La balise n'est pas obligatoire
 mais permet de mieux convertir les charactères et éviter les erreurs ou les problème de signe ! Donc :
 
 . <Meta charset ="UTF-8> permet de dire au navigateur que la langue utiliser et le français. C'est une balise sépcial car elle ne
 se referme pas !
 
 # 1.3 Balise d'écriture
 
 Le Html est un langage hypertext ! Cela siginifie qu'il peut mettre en page et écrire sur un navigateur très facilement et
 réciproquement très rapidement. Certaines balises sont essentiels pour pouvoir afficher du texte à l'écran. Comme dans tous les
 langages, nous n'avons pas besoin de taper les balises en basique (0 et 1). il faut utiliser quelque balise :
 
 ."h1" jusqu'a "h5" -> Ces balises permettent d'afficher un titre à l'écran. Selon les balises (h1, h2, h3), la police sera de plus en 
 plus petites.
 
 . "p" -> Cette balise permet d'afficher n'importe quel texte à l'écran. Il est essentiel à l'affichage de texte. 
 
 . "br" -> Cette balise oblige un retour à la ligne (Exemple dans prototype.htm).
 
 <h1> 1.3.1 Faire une liste</h1>
 
 Il est possible de réaliser une liste avec plusieurs point et cela avec deux balises (Exemple dans prototype.htm) :
 
 . "ul" -> Cette balise déclare une liste.
 
 . "li" -> Cette balise déclare un premier point. Entre les balises d'ouverture et de fermeture, le texte doit être écris pour le 
 premier point.
 
<h1> 1.4 Le Style en Html</h1>

En html, il est possible d'appliquer un style à notre texte sans des langages annexes comme CSS qui est spécialment crée pour le style
mais nous verrons se langage dans le prochain chapitre de ce cours. Donc comme il existe des balises d'écriture, il existe des balises
pour le style (les exemples sont dans prototype.htm) :

. "strong" -> Cette balise permet de mettre le texte en gras.

. "en"-> Cette balise permet de mettre un texte en italique.

. "mark" -> Cette balise permet de surligner un texte en jaune.

<h1> 1.4.1 La balise style </h1>

Même si elle ne permet pas de tout contrôler elle fait quand même beaucoup pour améilorer le style et la mise en page du texte. Par
rapport au CSS elle est parfaite car même si elle n'a pas toutes les qualités de ce langage, ce qu'elle fait est quand même fou !
Donc elle se déclare (Exemple dans prototype.htm) dans une balise :

"body "style = "background-color : #ffffff"" -> Ici on demande a ce que l'arrière plan soit blanc même si c'est la couleur de base.

."p style = "color : #FF0000"" -> Ici le texte sera en rouge.

<en> Il existe plusieurs couleurs possible :</en>

(Les couleurs peuvent être défini par leurs équivalent en anglais : rouge -> red)

Blanc : #ffffff <br/>
Noir : #000000 <br/>
Rouge : #ff0000 <br/>
Bleu : #0000ff <br/>
Vert : #00ff00 <br/>
jaune : #ffff00 <br/>

<h1> 1.4.2 Appliquer un style sur tout une section</h1>

Il est possible d'affecter et de définir un style sur l'ensemble d'une section avec cette fois-ci une balise style complète : "style".
Donc, on définit la section qui aura le style choisi. Si on veut que cela soit tous les paragraphes, on met ce qui suit dans le head :

"style = "text/css" <br/>
P { <br/>
   color : blue; <br/>
   }
   
Le cours sur le style n'est pas terminer mais on reviendra dessus lors du chapitre 2 sur le CSS.







 
 
 
 
 
 
 
 
 
