# Ressources de la formation du Club Informatique des Ponts

### Utiliser ce projet
* Installer Git
* Se placer dans un répertoire de travail
* `git clone http://github.com/KIClubinfo/formation-web.git`
* Ouvrir le projet dans un IDE qui intègre le versionning git : `git atom .`

## Starter
Dans /starter se trouve un exemple de point de départ de projet avec un fichier html connecté à un fichier css, ainsi qu'une page de maintenance par dessus.

## Template de maintenance du projet starter
Source : http://www.templatestock.co/soul-free-html5-responsive-coming-soon-template/
Template original à /ressources/maintenance.zip

## Bootstrap
Tuto : https://www.w3schools.com/bootstrap/


## Séance 1 - 04/10/2017

### Annonce

Bonjour, la formation web s'organise sous la forme d'une séance toutes les 3 semaines, la première étant aujourd'hui à 20h en Navier. Prenez votre ordinateur et mangez avant. Il est conseillé de venir à chaque séance pour tirer partie des suivantes.
Pourquoi une formation web ?
Comme vous le savez le KI a une expertise particulière en réseau et en web. On gère le réseau des résidences depuis 1997, on héberge les sites des assos depuis 2001, dès 2003 existait un site des élèves, après on diffusait la télé aux résidences. On a nos propres serveurs web, on gère les mailings lists, le site admissible avec son shotgun et l'envoie des milliers de mails qui s'en suivent. On développe activement uPont et on héberge les sites (en enpc.org), bases de données, boîtes mail en @enpc.org des assos et clubs qui en font la demande (voir des chats, wikis, clouds...). Et ça marche plutôt bien, dès 2004 le bitum faisait sa promo pour la nuit de la rentrée, la nuit du printemps, ses openbars et ses soirées avec l'ESIEE : http://web.archive.org/web/20071010055316/http://clubsoirees.enpc.org/accueil.php , le bda aussi c'était très artistique : http://web.archive.org/web/20050428212458/http://bda.enpc.org:80/, le bde il y a 10 ans aussi : http://web.archive.org/web/20070116141207/http://bde.enpc.org:80/ et plein d'autres clubs et assos.
Bien sûr les sites étaient beaucoup mieux à l'époque que ces pseudos archives mal sauvegardées.
Cependant tous les servies web mis à disposition du KI et les sites élaborés par les clubs ne sont pas toujours transmis lors des passations, car les compétences en web varient de promo en promo. C'est ainsi que les assos refont sans cesse ce qui n'a pas été transmis sans savoir que ça existait.
On a donc des sites sur notre hébergement qui n'attendent que des gens pour faire briller leurs clubs et leur com'
Pour qui ?
Listeux ? Si vous voulez faire des campagnes, ça peut être l'occasion de pratiquer en faisant un très beau site de campagne (protip : ouvrez un site de campagne par onglet à la page hotline ;) si c'est un site wixsite c'est éliminé d'office faut pas déconner xD).
Vous voulez organiser le Bal des Ponts, il faut quelqu'un pour mettre à jour le site qui a été refait entièrement l'année dernière.
Vous voulez allé au bitum, ok vous pouvez payer quelqu'un pour le site de la ndlr ça marche aussi ^^ mais pas que (coucou Darius)
Vous voulez rejoindre Dévelop'Ponts, le Trium, PEP, faites valoir vos compétences aux passas, il y a de beaux sites à maintenir ! (et pour Diverti'Ponts aussi ^^)
Vous voulez lister BDS et non content de votre site de campagne, vous êtes tout jaloux de la web app Suponts'Héroes 2017 et vous voulez rivaliser l'an prochain pour exhiber notre victoire en direct au monde entier ?
Le BDE a créé un poste de webmaster pour refondre leur site entreprise (coming soon...).
Vous voulez que PEP revienne vers vous pour gagner masse thune (ouais bon là les KIiens veulent leurs études quand même ^^)
Il y en a qui se chauffent pour reprendre les sites de la MediateK, continuer celui de Ponts Critiques et le BDA essaie de développer une web app. Mais il en reste d'autres à l'abandon : bds, prc, pfc, pic, bda
Et puis bien sûr si vous voulez venir au KI, c'est un peu utile ;) Et on cherche activement des dev' pour uPont !
Alors si un club a un projet à soumettre pour les séances 2 et 3 de la formation, proposez !

### Slides

https://docs.google.com/presentation/d/1I-wPHErIfL7NRCapYMFj0ljqAdstDDEOBmBe2CHMsGs/edit?usp=sharing

### Rattrapage

Merci à tous ceux qui sont venus hier soir, ça nous a vraiment fait plaisir de voir autant de monde motivé ! :D
Je sais que la fin a été rushée, désolé, on a un peu manqué de temps...
S'il vous plait nous avons besoin de votre avis ! Prenez deux secondes d'amphi pour répondre à notre petit questionnaire :
https://goo.gl/forms/yDVMTqQQwC7wdbK12
On espère vous revoir bientôt pour la prochaine séance ! Et d'ici là, si vous avez des questions, n'hésitez pas à nous contacter :
https://www.messenger.com/t/enpc.clubinfo
La bise Reverse Proxy, DHCP, HTML, et tout le reste
PS : on a essayé de prendre en vidéo la formation, on vous tient au courant ^^

## Séance 2 - 25/10/2017

### Annonce

Vous allez pouvoir entrer dans la cours des grands en créant une page sur l'hébergement du KI en enpc.org. Pour ce faire vous pouvez d'ores et déjà vous mettre par groupe de deux (plus ou moins une personne à titre indicatif) et installer Filezilla sur votre ordinateur
Debian (Ubuntu/Mint...) : sudo apt-get install filezilla
Mac : brew cask install filezilla (il faut avoir installé homebrew)
Tous : téléchargeable sur https://filezilla-project.org/download.php?type=client
Les curieux peuvent installer Wireshark s'ils veulent approfondir leurs notions de réseaux. On l'abordera rapidemment.
Si vous avez une distribution linux amenez-là, cela vous facilitera la tache. Atom est un bon éditeur.

### Slides

https://docs.google.com/presentation/d/117pZuP9A91rzJ171BremHm8uPIZWndsoD3dUhRV1F04

### Rattrapage

Les personnes intéressées mais qui étaient absentes sont invitées à se mettre tout seul ou par groupe et à demander au KI par cette page le mot de passe de l'accès FTP à http://formation-web.enpc.org afin de commencer leur petit site dans un répertoire. Un début de projet à été créé dans le répertoire de chaque groupe en ayant besoin. Téléchargez le contenu du répertoire sur votre ordinateur, et commencer votre site. Le thème est libre, des pistes de travail sont données en commentaire de index.html.
Vous pourrez vous appuyer sur les très bons tutos suivants :
* https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3
* https://www.w3schools.com/html/
A la prochaine séance qui aura lieu le mercredi 15 novembre à 20h, nous regarderons et discuterons ce que vous avez fait. Nous aborderons le vaste écosystème des templates web. Si vous semblez être assez à l'aise, nous pourrons consacrer l'essentiel de la séance à un TP Bootstrap qui est un mini-framework html/css/js, dans le but de réaliser cette page : https://www.w3schools.com/bootstrap/trybs_theme_company_full.htm

## Séance 3 - 15/11/2017

### Annonce

Certains ont déjà fait de jolis sites sur notre hébergement et nous les en félicitons. Demain nous aborderons le monde des templates web ainsi qu'un miniframework html/css/js qu'est Bootstrap. A demain !
