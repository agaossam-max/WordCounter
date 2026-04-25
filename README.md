WordCounter
C’est un programme Java qui lit un fichier texte
et compte combien de mots il y a dedans.

Explication

 Le programme ouvre un fichier texte.

File : sert à ouvrir le fichier
Scanner : sert à lire le contenu

 Lecture du fichier

Le programme lit le fichier ligne par ligne.

Il utilise une boucle while :

elle continue tant qu’il reste des lignes à lire

Compter les mots

Pour chaque ligne :

le programme coupe la ligne en mots avec split(" ")
il utilise l’espace pour séparer les mots

Ensuite :

il compte combien de mots il y a
il ajoute ça dans totalMots

totalMots = compteur final

Résultat

À la fin :

le programme affiche le nombre total de mots du fichier

👉 Exemple :
“Nombre de mots : 120”
