## Protocole maquette

- Choix des 3 éoliennes
- Etude des dimensions des éoliennes réelles
- Choix des matérieaux : PVC et gaine électrique
- Calcul des échelles
- Bricolage :)

## Protocole expériences

- Achat d'un bac de 70L
- Remplir d'eau à la moitié
- Mettre l'éolienne au centre du bac
- Voir que ça coule donc ajout de frites
- Flotte de trop donc ajout de masses
- Qd le tout est en équilibre, création de vagues à la main : petites, moyennes et hautes 
- Filmer le bac de sorte que la ligne d'eau soit horizontale et de profil / vagues et vent pdt 8sec avec les vagues 
- Début du film au début de la création des vagues et du vent 
- Creation du vent manuellement : petit et fort
- Filmer le bac comme précédemment pdt 8sec avec le vent
- Utilisation du logiciel tracker
- Pointage de l'éolienne en respectant la condition de Nyquiest Shannon : fe > 2fmax. 
Or fe = 30Hz et fmax = 2.5Hz donc on a bien fe >> 2*(2.5)Hz.
On obtient fe avec Tracker : le logiciel nous fait prendre 1 point toutes les 0.33sec donc fe= 1/0.033 = 30Hz.
On obtient fmax avec nos vidéos : en 8sec il y a eu environ 19 périodes de vagues donc fmax = 2.5 Hz

## Protocole courbes

Pour les vagues : translation verticale de l'éolienne / temps
Pour le vent : translation horizontale de l'éolienne / temps

- Importer les modules nécessaires
- Importer le fichier texte (provient de Tracker avec t, x, y) dont on a besoin
- Création du graphe avec le module plot 
